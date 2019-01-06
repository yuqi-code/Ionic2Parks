# Ionic2Parks

This is a starter template for the Ionic2Parks app from [Mobile App Development with Ionic 2](http://www.ionic2book.com/) published by O'Reilly Press.

## How to use this template

*This template does not work on its own*.

```bash
$ sudo npm install -g ionic cordova
$ ionic start Ionic2Parks tabs
$ cd Ionic2Parks
```

With Ionic CLI version 3, the use of third party templates was removed. Once you have created the starter Ionic application using the steps above, download this repo and copy over the src and www directories into the newly created folder, replacing the initial src and www directory. You will still need to follow any additional steps in the book.

*s1_init

```bash
$ git remote add origin https://github.com/yuqi-code/Ionic2Parks
$ git pull origin master --allow-unrelated-histories
$ git commit -a -m "init"
$ git push origin master -f

$ git tag -a s1_init -m "init" HEAD
$ git push origin tag s1_init
```
