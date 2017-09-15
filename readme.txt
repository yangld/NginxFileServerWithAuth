1.需要创建/root/html文件夹及测试文件aa.txt,bb.txt
2.将文件拷贝到nginx.conf所在的文件，替换nginx.conf
3.启动nginx
4.在浏览器上访问http://xx.xx.xx.xx，会提示输入用户名密码，现在的是test:123456
5.如果需要定义自己的用户名密码，使用htpasswd.sh，之后输入用户名，密码，文件名
注意事项：文件名不需要加后缀，生成的文件自动加后缀
nginx.conf中配置的auth_basic_user_file为文件名，不是目录
