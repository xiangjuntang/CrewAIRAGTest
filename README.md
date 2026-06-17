# 1、前期准备工作
## 1.1 开发环境搭建:anaconda、pycharm
anaconda:提供python虚拟环境，官网下载对应系统版本的安装包安装即可                                      
pycharm:提供集成开发环境，官网下载社区版本安装包安装即可                                               
**可参考如下视频:**                      
集成开发环境搭建Anaconda+PyCharm                                                          
https://www.bilibili.com/video/BV1q9HxeEEtT/?vd_source=30acb5331e4f5739ebbad50f7cc6b949                             
https://youtu.be/myVgyitFzrA          

## 1.2 大模型相关配置
(1)GPT大模型使用方案(第三方代理方式)                               
(2)非GPT大模型(阿里通义千问、讯飞星火、智谱等大模型)使用方案(OneAPI方式)                         
(3)本地开源大模型使用方案(Ollama方式)          

# 2、项目初始化
## 2.1 下载源码
GitHub 下载地址如下：                
https://github.com/xiangjuntang/CrewAIRAGTest                                                     

## 2.2 构建项目
使用pycharm构建一个项目，为项目配置虚拟python环境                       
项目名称：CrewAIRAGTest                                                   
虚拟环境名称保持与项目名称一致                                       

## 2.3 将相关代码拷贝到项目工程中           
将下载的代码文件夹中的文件全部拷贝到新建的项目根目录下                      

## 2.4 安装项目依赖          
打开命令行终端在项目根目录下执行如下命令安装依赖包                                            
pip install -r requirements.txt                     
每个软件包后面都指定了本次视频测试中固定的版本号,建议先使用要求的对应版本进行本项目测试，避免因版本升级造成的代码不兼容。测试通过后，可进行升级测试                      


