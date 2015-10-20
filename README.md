# Xtal Commerce - Node.js eCommerce

An eCommerce platform based on [LoopBack](http://loopback.io), and the ZRECore data model templates.

Requires the Strongloop loopback cli tool. Xtal Commerce development is done in ES6 (io.js)

- Strongloop Loopback cli tool
- Ruby SASS gem
- IO.js v3.3.1 or higher
- Gulp npm package
- Bower
- Browser Sync
- jshint

To setup, run this from the base directory after installing all requirements:

```
npm install
bower install
gulp
slc arc

# In a seperate terminal...
slc start
```

Using StrongLoop Arc, click on Process Manager. Add 'localhost' with port '8701' to 
the Process Manager list.

Then, access the following address using your favorite browser:

```
# Application Front-end
http://localhost:3001
```