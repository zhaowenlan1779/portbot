# portbot
A small bot to port PRs

## Dependencies
* Ruby (Recommended: 2.4, Requirement: Unknown)
* Ruby dependencies: uri, net/http, json (should come with Ruby install)
* Git

## Usage
1. Edit the script to adjust any settings
1. Make sure you have git and ruby in your PATH
1. Fork the PORT_TO repo and get a local clone of it (make sure there is a `origin` remote)
1. Add the PORT_FROM repo as a remote in the PORT_TO repo, and fetch it
1. Put this script in the PORT_TO repo
1. Open shell. Windows: powershell/cmd/WSL Bash (given that you have ruby and git installed there); Linux: bash/sh; macOS: Terminal. Do not use Git bash or MSYS shell. They seem not to work and are super slow running Ruby.
1. Run `ruby ./portbot.rb`
1. Enter the PR number you want to port, resolve conflicts if any.
1. Enjoy!
