基于WEB的网上购物系统主要功能包括：前台用户登录退出、注册、在线购物、修改个人信息、后台商品管理等等。本系统结构如下：
 （1）商品浏览模块：
	实现浏览最新商品
	实现按商品名称浏览商品
	实现根据商品分类浏览商品
 （2）购物车：
        登录后可以将商品加入购物车，或从购物车移除商品
 （3）登录、注册：
        购物前需要登录，如果没有账号则可以先注册
 （4）提交、查询订单：
        商品加入购物车后可以提交订单，也可以查看自己的所有订单

  (5) 后台管理员模块
        用户登录功能：通过账号登录系统。
        商品分类管理功能：可以查询所有商品分类，添加新的商品分类，删除已有的分类
        商品管理功能：可以查询所有商品，添加新商品，删除已有商品
        订单管理功能：可以查询所有订单，对未发货的订单进行发货处理
        用户管理功能：可以查询所有用户，查询指定用户，删除用户
        修改登录密码功能：修改管理员的登录密码
 
项目访问路径:
  前台：http://localhost:8080/webShopping
  后台：http://localhost:8080/webShopping/admin/login.jsp