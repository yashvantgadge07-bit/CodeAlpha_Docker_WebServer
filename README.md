# CodeAlpha Web Server Using Docker

## Project Overview

This project demonstrates how to create and run a simple web server using Docker as part of the CodeAlpha DevOps Internship.

## Technologies Used

* Docker
* HTML
* Nginx
* Git and GitHub

## Project Files

* `Dockerfile` — Configuration used to build the Docker image.
* `index.html` — Web page served by the container.
* `README.md` — Project documentation.

## How to Build the Docker Image

Open a terminal in the project folder and run:

```powershell
docker build -t codealpha-webserver .
```

## How to Run the Container

```powershell
docker run -d --name codealpha-webserver-container -p 8080:80 codealpha-webserver
```

## How to View the Website

Open your browser and visit:

http://localhost:8080

## Internship Task

CodeAlpha DevOps Internship — Task 4: Web Server Using Docker.
