# mymuduo
#手写muduo库项目
#本项目基于boost库实现手写muduo库中相关重要功能，example文件加下为测试服务器的代码，切换到example目录之中，使用make命令，然后运行当前文件夹下的tserserver，即可开始测试，发送内容之后在同时可实现接收功能，同时开辟新的终端使用telnet ip port


cd example
make 
./testserver

#在新终端运行
telnet ip port
#发送信息即可实时接收

#更新代码时运行example下autobuild.sh更新链接库，测试代码可继续按照以上步骤进
cd example
./autobuil.sh

#lib文件夹下包含构建好的so链接库，其中的.cc文件实现相应功能
