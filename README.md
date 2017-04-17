# thrift-zk
thrift使用zk实现SOA
1 使用thrift框架时，先定义名为.thrift后缀的文件，然后由thrift编译器编译成指定语言的源文件，
然后借助thrift提供的各种语言的实现lib库，完成rpc的调用。
2 三种平台编译器的安装,idea 有插件
3 服务开发这一类套路都很熟悉，通常会拆分成3部分，接口定义（也称服务&数据契约 contract）、
服务生产方(即：server端)、服务消费方(即：client端)
