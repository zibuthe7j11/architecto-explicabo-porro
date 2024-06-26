# @zibuthe7j11/architecto-explicabo-porro <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @zibuthe7j11/architecto-explicabo-porro
```

## Usage/Examples

```js
var regexTester = require('@zibuthe7j11/architecto-explicabo-porro');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@zibuthe7j11/architecto-explicabo-porro
[npm-version-svg]: https://versionbadg.es/ljharb/@zibuthe7j11/architecto-explicabo-porro.svg
[deps-svg]: https://david-dm.org/ljharb/@zibuthe7j11/architecto-explicabo-porro.svg
[deps-url]: https://david-dm.org/ljharb/@zibuthe7j11/architecto-explicabo-porro
[dev-deps-svg]: https://david-dm.org/ljharb/@zibuthe7j11/architecto-explicabo-porro/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@zibuthe7j11/architecto-explicabo-porro#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@zibuthe7j11/architecto-explicabo-porro.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@zibuthe7j11/architecto-explicabo-porro.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@zibuthe7j11/architecto-explicabo-porro.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@zibuthe7j11/architecto-explicabo-porro
[codecov-image]: https://codecov.io/gh/ljharb/@zibuthe7j11/architecto-explicabo-porro/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@zibuthe7j11/architecto-explicabo-porro/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@zibuthe7j11/architecto-explicabo-porro
[actions-url]: https://github.com/zibuthe7j11/architecto-explicabo-porro/actions
