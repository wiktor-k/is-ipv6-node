# is-ipv6 for Node.js

Check if `String` is an IPv6 address.

[![NPM Package Version Badge][npm-package-version-badge]][npm-package-url]
[![NPM Package Downloads Badge][npm-package-downloads-badge]][npm-package-url]
[![devDependencies Status][devDependencies-status-badge]][devDependencies-status-page-url]
[![Travis Build][travis-image]][travis-url]
[![Code Climate][climate-image]][climate-url]

## Installation

`npm install is-ipv6-node`

## Usage Example

```javascript
var isIPv6 = require("is-ipv6-node");

console.log(isIPv6("2a02:2770::21a:4aff:feb3:2ee"));
console.log(isIPv6("Hello World!"));
```

***

```javascript
true
false
```

## Tests

To run the test suite, first install the dependencies, then run `npm test`:

```bash
$ npm install
$ npm test
```

## License

Distributed under the [MIT License](LICENSE).

[npm-package-version-badge]: https://img.shields.io/npm/v/is-ipv6-node.svg
[npm-package-downloads-badge]: https://img.shields.io/npm/dm/is-ipv6-node.svg
[npm-package-url]: https://npmjs.org/package/is-ipv6-node
[devDependencies-status-badge]: https://david-dm.org/AnatoliyGatt/is-ipv6-node/dev-status.svg
[devDependencies-status-page-url]: https://david-dm.org/AnatoliyGatt/is-ipv6-node#info=devDependencies
[travis-image]: https://img.shields.io/travis/AnatoliyGatt/is-ipv6-node/master.svg
[travis-url]: https://travis-ci.org/AnatoliyGatt/is-ipv6-node
[climate-image]: https://codeclimate.com/github/AnatoliyGatt/is-ipv6-node/badges/gpa.svg
[climate-url]: https://codeclimate.com/github/AnatoliyGatt/is-ipv6-node