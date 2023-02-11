<h1>Your Github Widgets</h1>

**Your Github Widgets** was an idea I got by looking at [honeypot.io](https://www.honeypot.io)'s github contributions section (you need to sign in using github to see it) in the profiles page

The goal of this project is to enable developers with account in github to get their stats related information such as

1. Number of contributions 
2. number of commits 
3. number of stars across projects
   - You get the idea right 💡


, export them as widgets and integrate into any application

<h2>Table of Contents<h2>

- [Goal](#goal)
- [Use cases](#use-cases)
  - [Personal Blog](#personal-blog)
  - [Thirdy Party Apps](#thirdy-party-apps)
- [Bare Minimum](#bare-minimum)
- [Motivation](#motivation)
- [Foundation](#foundation)
  - [Where To Explore](#where-to-explore)
  - [Architecture](#architecture)
  - [Tech Stack](#tech-stack)


## Goal
The main goal of this project is to make meaning full applications using Github Statistical information

In order for the stats to become useful, wouldn't it be cool if a web app is able to export them as html widgets either as plain html mark up with css or through the  language frameworks of your choice such as react/vue/angular, tailwind css etc as reusable components that can be plugged into any projects.

Sounds valid € , but not so sure where to use those widgets 🤔

## Use cases

### Personal Blog
- Imagine your building your own personal blog where you'd like to showcase your github stats.

- You wanna show only specific statistics such as contributions you've made or stars you have earned

### Thirdy Party Apps

- Imagine your building a profile based application , where in you'd like to showcase the users github statistics

- Expose an API that can let third party applications integrate into widget context and make use of the widgets

...A Lot more use cases can come up over time 💡💡


## Bare Minimum

To begin with a bare minimum set of features, it's ideally nice to have an application that implements [Use case 1](#personal-blog) 

Exporting the statistics as html widgets could be a first step for a bare minimum app

## Motivation
There are quite few motivational aspects behind the idea for this project.
1. Try out a new tech stack
2. Learn new framework
3. Experiment with some architectures


## Foundation
Principle foundation for this project is Github. So in order to make this project really usable , applications need to talk to github apis to provide useful statistics as widgets

So Github APIs have to be explored well to figure out the foundational architecture for the project

### Where To Explore
1. Rest API can be explored [here](https://docs.github.com/en/rest?apiVersion=2022-11-28)
2. GraphQL API can be explored [here](https://docs.github.com/en/graphql)

### Architecture
- TBD

### Tech Stack
- TBD

