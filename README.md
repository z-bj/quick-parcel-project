# Introduction
This is the a quick starter project I use to quickly experiment stuffs when I trying to replicate cool effects I see on the web.


# Installation
``` 
npm install
npm run start
```

And then go to `localhost:1234`

# Handling changes
If you need to change things such as navbar for example, you will find all the reusable component througout the pages in the folder : `/src/partials`.
Change the html here and modifiy the css in the good file in `/src/scss`.
That is almost everything you need to know.

If you have run : `npm run start`, parcels has an excellent hot reload except if you are on another page than index.html. There is a bug with parcels that requires you to manually refresh the page when you are not working on `index.html`.


# Rollback to parcel v1
I use this quick start kit to quickly launch new project.
At the end, the goal is to publish on codesandbox the result.

Unfortunately, parcel v2 is not well handled by codesandbox. When rolling back, I also had to remove the posthtlm feature which where buggy.
Finally it is a very basing project where scss and typescript works out of the box but don't expect to do something really fancy with posthtml.
For a bigger project with parcel v2 and many good features, use the main branch.

# Alias to quickly upload the code on Codesandbox
You must install codesandbox command line on your computer. Then add this alias to your `.zshrc`:

```
alias share_code='rm -rf dist .cache && codesandbox ./'
```
# quick-parcel-project
