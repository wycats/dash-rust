# [Dash](http://kapeli.com/dash) docset for [Rust](http://rust-lang.org)

## Installation

Download the latest release of the docset [from the releases page](https://github.com/indirect/dash-rust/releases). If you want to generate the docset yourself, follow the steps in "Usage" below.

## Usage
This ruby gem is build with [bundler](https://bundler.io/).

```bash
$ git clone git@github.com:indirect/dash-rust.git
$ cd /dash-rust/
$ bundle install
$ rake
$ open Rust.docset
```

To download the documentation for the latest Rust nightly and build a
fresh docset from that:

```bash
$ git clone git@github.com:indirect/dash-rust.git
$ cd /dash-rust/
$ bundle install
$ rake nightly
$ open Rust.docset
```

### License

MIT License, copyright 2014 by André Arko
