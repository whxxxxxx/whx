FROM node:16.17.0
COPY .. /app
WORKDIR /app
RUN npm config set registry https://registry.npm.taobao.org
RUN npm install --registry=https://registry.npm.taobao.org
EXPOSE 3000