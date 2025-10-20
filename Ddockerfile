# Step 1: Use official Node.js image
FROM node:18

# Step 2: Set working directory
WORKDIR /app

# Step 3: Copy files into container
COPY package*.json ./
RUN npm install
COPY . .

# Step 4: Expose port
EXPOSE 3000

# Step 5: Command to run the app
CMD ["npm", "start"]
