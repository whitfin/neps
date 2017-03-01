Neps
====

Simple way to open a Node.js REPL with your favourite modules included.

### Setup

`neps` is on `npm`, so go ahead and install it globally:

```bash
$ npm install -g neps
```

### Usage

Super easy to use via a command line:

```bash
$ neps [modules...]
```

### Examples

Here are a few examples which should demonstrate usage:

```bash
# loads 'moment' directly from `npm`
$ neps moment

# loads 'neps' directly from GitHub
$ neps zackehh/neps

# loads multiple modules
$ neps moment lodash

# provides a custom name for a module
$ neps _=lodash
```

### Options

By default modules you ask for are loaded into `$HOME/.neps` (and thus aren't installed if they're already there).

You can customise this location on each run of `neps` by using the `-p` flag:

```bash
# installs to /tmp/neps instead
$ neps -p /tmp/neps moment
```
