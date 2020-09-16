# Creating an Extraordinary Contributor Experience

This document is for open source project maintainers who want to increase community contributions to their project. 

We'll look at the Contributor Experience and how you can create an Extraordinary Contributor Experience.

## So You're a Maintainer

You're an open source project maintainer. 

You're probably also a contributor to the project - maybe the only one. 

Wouldn't it be great to have other people making contributions to the codebase?

Or maybe you're part of a team that works professionally on a code base. Maybe you have users asking for features and bug fixes. Wouldn't it be great if the contributions grew at the same rate as the requests?

Contributors not only provide value to the project by testing, opening issues, and contributing code, they also become advocates for the project in the wider community. And why not? It's their project too, now. They'll tweet out when their code goes into a release, and add it to their CV.

Maybe you've been an external contributor to an open source project prior to become a project maintainer - maybe you haven't.

Either way, you probably haven't thought about creating a contributor experience, systematically. 

That is what we are going to look at here. 

Why? Because repeat contributions, like repeat customers, come from an extraordinary experience. Not everyone will repeat - but if your contributor experience is extraordinary, you will increase the amount of contributions.

## Who Contributes

Let's first consider _who_ contributes.

We will create a few archetypes.

**First-timer**: The first-timer is someone who has never contributed to any open source project before. This is all new to them. They don't know how to "open a pull request", they are not sure if their contribution will be good enough to be accepted, and if they do take the plunge, how this pull request goes will determine how their entire open source contribution career goes. No pressure.

**Seasoned Pro**: The seasoned pro is not only a solid developer who knows not only how to write good code, but also how open source works. They've done a bunch of PRs to various open-source projects, so they know what to expect. This person compares their experience with your project with their experience with other projects.

## Characteristics of External Contributors 

People are usually busy. They might be using your project for their day job. You are focused on the project itself - it's the main event. For a lot of potential contributors, however, your project probably is one piece in a complex stack of technology that they are wrestling with. It's an extra on the show. 

Any contribution that people make to the project is a generous contribution of their valuable time.

## How to create an Extraordinary Contributor Experience

We're going to cover a number of specific tactical actions that you can take, strategically.

However, there are two things that will make everything work. These are orientations, rather than actions. If you just get these two things, everything will work. If you do everything else and neglect these, your results will be variable.

### Always Deal with The Person Behind the Pull Request

Behind the bug report, feature request, or pull request is a person.

Always deal with the person. Deal with the person about the pull request, rather than just dealing with the pull request.

It's obvious and easy to think that we are building software. Something that is just as easy to forget is that in open source we are _building software together_. So while we are building software, we are also building an experience of building software.

Before joining Camunda's DevRel team, Josh was an external contributor to the Zeebe project. While evaluating Zeebe against other open source workflow engines, he opened various issues and pull requests.

The pull requests to other projects languished, but the Zeebe ones got feedback, and got merged. He says that his experience was that his contribution was acknowledged and appreciated. That gave him confidence that if his company at that time went with Zeebe, they would be able to contribute fixes to the engine for their use case, and they would get merged.

Think about the person behind the pull request. Put yourself in their shoes. Think back to the best experience that you've had when contributing to a project. Maybe it was your first pull request, or another time. You probably experienced being acknowledged and appreciated, as a person, as well as respected professionally for your contribution.

On the flipside, a prominent open source company let one of its best engineers go because of their interactions with the community. This was an A-grade rockstar contributor - legendary in the open source world for their work on the Linux kernel. Unfortunately, they were also legendary for their interactions with contributors - and not in a good way. A typical PR response went along the lines of "_your code is stupid, and so are you_". 

Don't be that guy.

If you treat your contributors well, they will come back.

### Have the Contributor Win

People contribute for different reasons. 

Some people are fixing a problem or implementing a feature for their use case, and they want it merged upstream so that they don't have to maintain a separate fork.

Some people are out to learn, and to build a reputation for themselves that is portable and visible.

Some people are just good open source citizens. Fixing things they come across is like picking up a piece of litter on the street.

Some people are evaluating the project for use, and want to get a sense of how amenable and responsive it is to Pull Requests.

For all of these cases, if you take the stand that you are _the champion of this contributor_ and it is your role to "have them win", then you will find the way to empower them, wherever they are coming from.

A contributor may have time to work on further changes to a Pull Request, such as documentation or tests - and they may not. 

Sometimes, it is a "drive-by" contribution. Someone fixing something in a dependency of their project and moving on with their day job. They may not have time to do additional changes to make it just right.

If you deal with the person behind the Pull Request, and see yourself as their champion, then you will be sensitive to their ability and appetite for extended collaboration. 

Maybe they want to learn, and are eager to make further changes. Maybe not. But if your goal is to "have them win" - to get their contribution merged and their name in lights, then you will figure that out with them.

You have to balance something here: if a pull request comes in that requires a significant amount of work to get over the line, you may have a problem.

The contributor may not have had in mind that getting the PR over the line would turn into another full-time job for them. And you already have other things that you are working on, so fixing a half-done pull request is putting more work on your plate.

One of the things to factor in - as you work out whether it is worth the effort for you to get it over the line - is the longer-term investment in community capital. 

Merged pull requests beget more pull requests. And one of the metrics used to evaluate project health - for people who are considering betting on your project by basing their project on it - is how many open pull requests there are, and how long they have been open.

If you can't see your way to get it done, and the contributor says that they can't get it done, then you have a couple of options.

You can close the pull request, and they can reopen it later, when they have time to work on it. Or you can pull it into a branch to work on later. If you do the latter, they will get props when it does get merged to the main code base.

Either way, acknowledge them and thank them.

If you do invest the time, either to work with them, or to get it over the line for them, know that you are making a long-term investment in the community capital of the project.

### Prepare for guests

Here we get into some tactical steps that you can take to create an extraordinary contributor experience.

Before anyone comes to contribute, you can prepare the project for them.

Think of the project repository like a store, with a customer experience design. Users are one set of customers, and contributors are another. 

A good example of design is the Apple Store layout. Everything is clearly marked, and discoverable. When people come in to an Apple Store, they are not wandering around a labyrinth, left to puzzle things out for themselves.

Add templates to the repo for Pull Requests and Issues. This gives users guidance when they open a Here is a great collection of templates: [https://github.com/stevemao/github-issue-templates](https://github.com/stevemao/github-issue-templates).

### Put the sign out in front

Every business needs to let people know that they exist, and that they are open for business. Let people know that you accept contributions. Put it at the top of the README.md file, so that it's one of the first things that they read, with a link to the contribution instructions.

It's one thing to include a CONTRIBUTING.md file in your repo, it's another thing to "_stand out on the sidewalk and hand out fliers_". "_Putting the sign out in front_" doesn't mean the front of the project - it means _in front of the contributor_. People will land in different places in your project from a search engine, or by focusing in on a specific area of interest. If you catch them at the right moment, in the right place, with the right message, a brief moment of inspiration can convert into a contribution.

Everywhere that represents a touch point or an area that the community can contribute to, weave it into the narrative.

Put it in the Getting Started instructions: "_If you find something wrong or missing in here, feel free to submit a pull request._" (with a link to the documentation contribution section of your contribution instructions).

Put it in the API documentation. Put it in the issue template. Put it everywhere (but don't overdo it). 

You want to "_walk the floor_". Start with a blank mind, and approach your project as a new user. Go to your repository, your documentation, and your package / image hosting page, and walk through them as a new user. 

Is it obvious that I can contribute to this project? Is it obvious how I do that, or how I find out how to do that?

### Make it Easy

The lower the barrier to entry, the more people will cross over it.

If you put links in your documentation so that someone can see something wrong or missing, click a link, correct it and submit a Pull Request, people are more likely to do it.

If you make it a single click from your README to report a bug, with a template that they can fill out, people are more likely to do it. 
@TODO: value prop to maintainer. 

If you want people to search existing bug reports first, then give them a link to the existing issues filter, with instructions to search, followed by a link to open a new issue.

If you want people to contribute code, you need to document how to develop the project. This means installing all prerequisites and building the project. The more of this that you can script, the easier you make it. Potential contributors can burn all of their inspiration trying to get the project to build, before they even think about writing code.

Again, "_walk the floor_". Starting with a blank mind, approach the project as a new user. How easy is it to check out and build? Can you make it easier?

This can be challenging, because your computer is configured to build the project, and may have dependencies or tools that are required, but not covered by your instructions. Again, this is a perfect opportunity to weave in  

### Acknowledgement

People contribute to open source for many reasons, but something that every person thrives on is acknowledgement. There is a saying "_what gets recognised gets repeated_". 

Acknowledging people for their contribution goes a long way.

One thing you can do is label any Pull Request coming from a remote fork with a label saying "Thank you".

And you can add a comment on the pull request,  leaving the person behind the pull request acknowledged and appreciated.

### Timeliness

People are busy - including you! 

Remember, though, that we are not just building software here - in open source, we are building _a community that builds software_. 

Just like you attend to infrastructure or production outages, or customer issues, to create an extraordinary contributor experience, you'll need to attend to contributor requests.

Contributors may have a limited attention span or period of inspiration. It is important to acknowledge their contributions as soon as possible, and then to let them know what time frame they can expect to get a response within.

When evaluating the Zeebe project as an external contributor, Josh submitted a pull request to fix a bug on a Friday. When he got back to work on Tuesday after a long weekend holiday in Australia, the pull request had been merged and released.

That went a long way to building confidence in the project, and that company decided to base their project on Zeebe.

You can't always turn things around that fast, but you can acknowledge receipt and set an expectation. Automation is your friend in this case. You can create a "Contributor SLA" and create automation to trigger reminders.
