# fileUpload
文件上传知识

accept属性

该属性表明了服务器端可接受的文件类型，可以限制你手机选择相关的文件，如果限制多个，可以用逗号分割，例:

image/* 图片类型

video/* 视频类型

audio/* 音频类型

上传相同文件时不会触发upload的change事件，所以必须cloneNode upload dom,然后change事件需要重新绑定
