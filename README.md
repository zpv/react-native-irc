[![npm](https://img.shields.io/npm/v/irc.svg?style=flat)](https://www.npmjs.com/package/irc)
[![License](https://img.shields.io/badge/license-GPLv3-blue.svg?style=flat)](http://opensource.org/licenses/GPL-3.0)


React Native fork of [node-irc](https://github.com/martynsmith/node-irc#readme)

You can access more detailed documentation for this module at [Read the Docs](http://readthedocs.org/docs/node-irc/en/latest/)
## Installation

The easiest way to get it is via [npm](http://github.com/isaacs/npm):

```
npm install react-native-irc
```

## Basic Usage

This library provides basic IRC client functionality. In the simplest case you
can connect to an IRC server like so:

```js
var irc = require('react-native-irc');
var client = new irc.Client('irc.yourserver.com', 'myNick', {
    channels: ['#channel'],
});
```

Refer to [node-irc](https://github.com/martynsmith/node-irc#readme) for more usage instructions.