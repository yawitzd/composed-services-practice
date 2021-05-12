FROM node:14
WORKDIR /usr/src/app

COPY package*.json ./
RUN ["nvm", "install", "v15.8.0"]
RUN ["nvm", "use"]
RUN npm install

EXPOSE 80
CMD ["npm", "run", "dev"]
