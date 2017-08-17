# weixin-service
以http方式提供获取access_token和jsapi_ticket方法


curl 'http://weixin-service.domain.com/weixin/getAccessToken'
{"ret_code":200,"ret_msg":"OK","result":{"access_token":"jqdgno1Z9xNr66_Pg3D2rrKvAa0PQt6KC-O0W5arqpk_kDUvJiWKEExRngbakjKpwkWLYZ1lZt_jgpYYQ9m82HBU4po5kQ_kcFsvXkASUXI3-cC-Lar6KXeR7swzBa-EFWUaAJAYPN","expires_in":7200}

curl 'http://weixin-service.domain.com/weixin/getJsApiTicket'
{"ret_code":200,"ret_msg":"OK","result":{"ticket":"kgt8ON7yVITDhtdwci0qeY7YLIR0gJDL0qgA6b6UtY_kDudoJPpfSzUFJer0wlvms1V0ssLE4LbdLfJMGh4MLw","expires_in":7200}
