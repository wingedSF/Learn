1. 报错 Class constructor EventEmitter cannot be invoked without 'new'
        当用ES6语法class关键字定义一个类，并且导出这个类。在另一个文件导入，直接EventEmitter.call(this)，报错
        如果携程ES5的语法，function EventEmitter去定义，则不会报错

2. nodejs 程序调试工具，vscode、命令行等  
3. 各种模块化规范
4. yarn 了解，不如npm 稳定