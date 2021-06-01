<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Local Setup with docker
For local setup we need to install docker in the system. Here are the following steps you need to do for this project running.

- start by running command "docker compose up -d"
- There are 3 different containers exist in our project 1-Mysql (deserthabood-db) 2-Nginx (deserthabood-webserver) 3- Php Apache (deserthabood-web)
- docker exec -it deserthabood-db bash for opening mysql terminal
- docker exect -it deserthabood-web bash for running artisan commands and composer installations
- mysql -uroot -proot for making current user as root
- create database deserthaboob
- To view database schema and table install DBeaver Tool
- Our project is setup and running url is http://localhost:81/
## Database Setup in DBeaver
-Goto new connection and select mysql type connection
- Type Server host "localhost"
-Port 3307
-Database name deserthaboob
-password and root given in .env and your are connected

## License

This application software licensed under the [MIT license](https://opensource.org/licenses/MIT).
