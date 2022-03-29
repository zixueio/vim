vim删除空行
> :g/^$/d
`:g`将在正则表达公式配合行上执行命令。正则表达式是`空行`，命令是`:d`（删除）

vim升级到最新版
```
sudo add-apt-repository ppa:jonathonf/vim
sudo apt update
sudo apt install vim
```

安装vim安装中文文档
查找需求版本：http://vimcdoc.sourceforge.net/
```
wget https://sourceforge.net/projects/vimcdoc/files/vimcdoc/vimcdoc-2.1.0.tar.gz/download -o vimcdoc-2.1.0.tar.gz
tar -zxvf vimcdoc-2.1.0.tar.gz
cd vimcdoc-2.1.0 && ./vimcdoc.sh -i
```

vim中文帮助文件的文本是以utf-8进行编码的, 如果想用vim直接查看, 需要在配置文件 ~/.vimrc中 增加配置项
```
set encoding=utf-8
```

