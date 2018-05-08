# woocommerce docker

```sh
$ docker-compose up -d
```

1) Enter http://localhost:8080 in the browser and follow install instructions.

2) Login to wordpress admin > Plugins and activate WooCommerce plugin and follow the wizard (skip payments step).
You must also create a product in order to make the API work

3) Go to WooCommerce plugin settings > API > Keys/Apps > Add Key

Description: woocommerce

User: default already selected

Permissions: Read/Write

Generate API Key

4) Go to Wordpress Settings > Permalinks and select `Post name` or `Day and name` under **Common Settings** and Save changes

5) Add a product to make the API work (skip if already added a product in step 2)
