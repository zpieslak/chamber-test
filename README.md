# README

* Ruby version

    2.5.0

* Configuration

    Checkout repository.

    Run `bundle`.

    Change your local hostanme to return `examplehost`

* How to test

    Run `chamber show` - the settings should be output properly.

    Run `rails c` and try to enter any setting, i.e. `Chamber.env.setting` - `Chamber::Errors::DecryptionFailure` is raised.

    Uncomment lines 19-21 in config/application.rb, the Chamber should work now.
