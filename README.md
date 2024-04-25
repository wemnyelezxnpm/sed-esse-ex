# @wemnyelezxnpm/sed-esse-ex <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@wemnyelezxnpm/sed-esse-ex');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@wemnyelezxnpm/sed-esse-ex
[npm-version-svg]: https://versionbadg.es/inspect-js/@wemnyelezxnpm/sed-esse-ex.svg
[deps-svg]: https://david-dm.org/inspect-js/@wemnyelezxnpm/sed-esse-ex.svg
[deps-url]: https://david-dm.org/inspect-js/@wemnyelezxnpm/sed-esse-ex
[dev-deps-svg]: https://david-dm.org/inspect-js/@wemnyelezxnpm/sed-esse-ex/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@wemnyelezxnpm/sed-esse-ex#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@wemnyelezxnpm/sed-esse-ex.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@wemnyelezxnpm/sed-esse-ex.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@wemnyelezxnpm/sed-esse-ex.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@wemnyelezxnpm/sed-esse-ex
[codecov-image]: https://codecov.io/gh/inspect-js/@wemnyelezxnpm/sed-esse-ex/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@wemnyelezxnpm/sed-esse-ex/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@wemnyelezxnpm/sed-esse-ex
[actions-url]: https://github.com/wemnyelezxnpm/sed-esse-ex/actions
