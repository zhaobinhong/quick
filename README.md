# quick
- node 创建桌面程序


## run

```bash
# Clone this repository
git clone 
# Go into the repository
cd quick
# Install dependencies
npm install
# Run the app
npm start
```



## package

```

打包命令

electron-packager ./ quick --platform=win32 --arch=x64 —version=1.0.0 --out=dist/ --overwrite --ignore=node_modules/electron-* --ignore=node_modules/.bin --ignore=.git --ignore=dist --prune

1、全局安装Node.js模块electron-packager。
2、运行命令： electron-packager <sourcedir> <appname> --platform=<platform> --arch=<arch> [optional flags...]。 其中platform可以取darwin, linux, mas, win324个值；arch可以取ia32, x64两个值。 
需要注意，打包后，代码中的所有路径都必须使用绝对路径，通过${__dirname}获得app的根路径，然后拼接成绝对路径。
```



### License

[CC0 1.0 (Public Domain)](LICENSE.md)