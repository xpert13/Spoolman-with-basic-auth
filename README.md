# Spoolman with basic auth

Add basic auth to your Spoolman server using Nginx.

## Using

Just generate a correct `.htpasswd` file and put it in the `nginx` folder. 
Then you can run your service (`docker compose up -d`) and use it.

Moonraker settings should be like this:
```conf
[spoolman]
server: http://username:password@your-server-host:7912
```
