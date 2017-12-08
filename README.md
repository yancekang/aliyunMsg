# aliyunMsg
微博：@科技男
微信公众账号：科技强人
QQ群：340036554
**thinkphp集成阿里云发送短信验证码**

配置信息：sendSMS.php   配置key等参数，

在需要调用发送短信验证码是位置调用

```php
$msg=new Sendsms();
$tel='12345678999';
$rendcode=rand(1111,9999);
$msg=$msg->sendcode($tel, $rendcode);
```

