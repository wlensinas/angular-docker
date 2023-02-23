1. Build the app: `docker build -t my-app .`
2. Execute: `docker run -d -it --name my-app -p <RandomPort>:80 my-app` eg: `docker run -d -it --name my-app -p 8082:80 my-app`
3. Stop: `docker stop my-app`