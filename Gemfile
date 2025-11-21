source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# 在 Gemfile 中添加这一行（覆盖原有间接依赖）
gem 'nokogiri', '>= 1.14.0', '< 2.0'  # 1.14.0+ 支持 Ruby 3.3

# gem "github-pages", group: :jekyll_plugins
gem 'github-pages', '~> 228'  # 228 及以上版本适配 Ruby 3.3

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

# gem "jekyll"
gem 'webrick'
gem "wdm", "~> 0.2.0" if Gem.win_platform?
gem 'tzinfo-data'  # 解决 Windows 时区数据缺失问题

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'hawkins'
end
