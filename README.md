## Development
1. [Install Ruby](https://www.ruby-lang.org/en/documentation/installation/)
1. [Install Bundler](https://bundler.io/)
1. Run `bundle install` to install dependencies
1. Run `bundle exec jekyll serve`
1. Open a browser to [http://127.0.0.1:4000](http://127.0.0.1:4000)
### Linting
Linting tasks run as a pre-commit hook. These are:
- [scss-lint](https://github.com/sds/scss-lint)
- [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)
It's recommended that developers enable editor support (see instructions in the links above) to view linting errors inline prior to committing code.
