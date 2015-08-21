# LAMP Deployment Script #
Automatically deploy web services using the LAMP model.

## Overview ##
+ Push a new commit to the GitHub repository.
+ Add a `.htaccess` file to deny access temporarily.
+ Remove old files on the production server.
+ Use `scp` to copy local files to the production server.
+ Load SQL queries on the production server.
+ Remove the `.htaccess` file.

## Getting Started ##
For the first time you run the script, execute the following command first:
```bash
$ git clone https://github.com/yuwen41200/lamp-deployment-script.git
$ chmod +x lamp-deployment-script/deploy
$ sudo cp lamp-deployment-script/deploy /usr/local/bin/
```
From now on, you can simply use:
```bash
$ deploy run
$ #TBA
```

## Requirements ##
TBA.

## License ##
[The MIT License](https://raw.githubusercontent.com/yuwen41200/lamp-deployment-script/master/LICENSE)
