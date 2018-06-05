## Build a live comment application using Ruby and Pusher

A demo of a live comment application built with Ruby and Pusher.


Screenshot of the demo app.

![comment-ruby](https://user-images.githubusercontent.com/19610753/40324253-df9de94a-5d2f-11e8-8359-66dad05f90c0.gif)


## Getting Started

### Clone the repository
```bash
$ git clone https://github.com/yemiwebby/live-comments-pusher.git
```

### Change directory
```bash
$ cd live-comments-pusher
```

### Install dependencies
```bash
$ bundle install
```

### Setup database

```bash
$ rails db:setup $ rails db:migrate
```

### Setup Figaro and Env variables

* Run `$ figaro install` to automatically generate `application.yml` file.
* Open `config/application.yml` and replace the content (if any) with the following:

```bash
PUSHER_APP_ID: 'your Pusher app ID'
PUSHER_KEY: 'your pusher kep'
PUSHER_SECRET: 'your pusher secret'
PUSHER_CLUSTER: 'your pusher cluster'
```

## Prerequisites
A basic knowledge of Ruby and CoffeeScript

## Built With

* [Rails](https://rubyonrails.org/) - Rails is a web application framework running on the Ruby programming language.
* [Pusher](https://pusher.com/) - A Node.js client to interact with the Pusher REST API