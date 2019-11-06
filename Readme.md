# Magento 2 Previous Next Product

This module provide a links to previous product and next product on the product page.

## Installation

Copy the content of the repo to the app/code/Zone/PreviousNextProduct/ folder

Enable module:
```
php bin/magento module:enable Zone_PreviousNextProduct
```

Disable module: (Optional)
```
php bin/magento module:disable Zone_PreviousNextProduct --clear-static-content
```

Update system:
```
php bin/magento setup:upgrade
php bin/magento cache:flush
php bin/magento cache:clean
```

## Author

* **Zekinah Lecaros** - *Initial work* - [Zekinah Lecaros](https://github.com/zekinah)

## License

[MIT](http://opensource.org/licenses/MIT)
