# Hugoblog
Hugoblog is responsive, simple, and clean that very fit for your personal blog based on Hugo Theme Static Site Generator (SSG)

![Screenshot](https://github.com/zuramai/hugoblog/blob/main/images/tn.png?raw=true)

Click **[here](https://blog.saugi.me/)** for live demo.

## Installation

*Before starting, please be sure that you have
[installed extended version of Hugo](https://github.com/gohugoio/hugo/releases) and
[created a new site](https://gohugo.io/getting-started/quick-start/#step-2-create-a-new-site). After that, you ready to
install **Hugoblog**.*

In your Hugo site `themes` directory, run:

```
git clone https://github.com/zuramai/hugoblog
```

Or, if you don't plan to make any significant changes, but want to track and update the theme, you can add it as a git
submodule via the following command:

```
git submodule add https://github.com/zuramai/hugoblog
```

Next, open `config.toml` in the base of the Hugo site and ensure the theme option is set to `hugoblog`:

```
theme = "hugoblog"
```

For more information read the official [setup guide](https://gohugo.io/themes/installing-and-using-themes/) of Hugo.



## Getting started

After installing the theme successfully it requires a just a few more steps to get your site running.


### The config file

Take a look inside the [`exampleSite`](https://github.com/zuramai/hugoblog/tree/main/exampleSite) folder of this theme. You'll find a file called [`config.toml`](https://github.com/zuramai/hugoblog/blob/master/exampleSite/config.toml). To use it, copy the [`config.toml`](https://github.com/zuramai/hugoblog/blob/master/exampleSite/config.toml) in the root folder of your Hugo site. Feel free to change the strings in this theme.

## Change site logo
Upload your site logo to the `/static` folder in your project, then edit `config.toml` and change `site_logo` value your image path. For example:
```toml
[params]
  site_logo = "/images/logo.svg"
```

## Comments Section
You could use Disqus comment by activating them in the `config.toml` and put your disqus shortname.
```toml
disqusShortname = "your-disqus-site-shortname"
```

# License
This template is under MIT License
