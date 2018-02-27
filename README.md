# php-proxy

## Acks
This work uses the following works from *Creative Commons*

1. `APACHE 2`
2. `PHP 7.2.2`
3. `PHP docker project`
4. [`php-proxy`](https://www.php-proxy.com/)

## contacts the author

* **Email**: [admin@yakeworld.top](mailto:admin@yakeworld.top)
* **Website**: http://yakeworld.top 


## hows

if you want to use docker [hub repo](https://hub.docker.com/r/yakeworld/php-proxy/):

    docker run --name php-proxy -p 9000:80 -d yakeworld/php-proxy

if you just want to try try this repo, use this

1. first check out this repo and cd into it

       git clone https://github.com/yakeworld/php-proxy.git  php-proxy && cd php-proxy

2. second you have to build it first

       docker build -t php-proxy .

3. then you run it

       docker run  --name php-proxy -p 9000:80 php-proxy

you may need to open a browser to address to *http://ip-address-of-your-docker-host:9000*



