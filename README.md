# Jekyll Twitter Plugin 2

A Liquid tag plugin for the Jekyll blogging engine that embeds Tweets, Timelines and more from Twitter API.

and, this repo derived from https://github.com/rob-murray/jekyll-twitter-plugin.  
The License here : [FORKED_FORMER_LICENCE](/FORKED_FORMER_LICENCE)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'jekyll-twitter-plugin-2'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-twitter-plugin-2

## Usage

### Here are a few examples

#### Tweet

An example of a Tweet - `{% twitter https://twitter.com/rubygems/status/518821243320287232 %}`

![Embedded tweet](https://raw.githubusercontent.com/rob-murray/jekyll-twitter-plugin/master/media/embedded-tweet.png "Screenshot of embedded tweet")

#### Timeline

An example of a Timeline - `{% twitter https://twitter.com/jekyllrb maxwidth=500 limit=5 %}`

![Embedded timeline](https://raw.githubusercontent.com/rob-murray/jekyll-twitter-plugin/master/media/embedded-timeline.png "Screenshot of embedded timeline")

#### Grid Timeline

An example of a Grid Timeline - `{% twitter https://twitter.com/TwitterDev/timelines/539487832448843776 limit=5 widget_type=grid maxwidth=500 %}`

![Embedded Grid Timeline](https://raw.githubusercontent.com/rob-murray/jekyll-twitter-plugin/master/media/embedded-grid.png "Screenshot of embedded Grid Timeline")

#### Moment

An example of a Moment - `{% twitter https://twitter.com/i/moments/650667182356082688 maxwidth=500 %}`

![Embedded moment](https://raw.githubusercontent.com/rob-murray/jekyll-twitter-plugin/master/media/embedded-moment.png "Screenshot of embedded moment")

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/jekyll-twitter-plugin-2. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Jekyll::Twitter::Plugin::2 project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/jekyll-twitter-plugin-2/blob/master/CODE_OF_CONDUCT.md).
