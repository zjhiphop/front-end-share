<!--
    This slide is talk about how to agilfy in front-end daily develop.
    TODO:
    1. What is Work flow?
        - A workflow consists of a sequence of concatenated (connected) steps. 
        - 工作流（Workflow），是对工作流程及其各操作步骤之间业务规则的抽象、概括、描述。
    2. EF School team's front end work flow

       tools:
        - confuluence (requirements)
        - sublime/webstorm/... (dev)
        - teamcity (integrate)
        - stash/git (surce manage)
        - jira (bug trace)
        - Ajax Dynatrace (performance)
        - ...

       tec:
        - css/Less/Recess
        - js/troopjs/requirejs/JSlint/jquery...
        - html/troopjs-template
        - nodejs/grunt/r.js/buster/mocha
        - ...
        
        We are efficient and streamline, but not creative and automated.

    3. What we need to improve?
        
        Process defects:
        - without client side error tracking
        - less unit tests 
        - front-end framework is too young
        - not automated
        - few cross team share and communicate 
    
    4. what is a good front end work flow?

        model:
        - build
        - stop
        - validate
        - rebuild
        - repeat  

        my understading:
        - Thinking fast and slow
        - Gives your more time creative
        - Streamline and automated
        - Good flow = Good bussiness

    5. My best work flow

        tool:
        - customized editor (sublime/notepad++)
            - code lint
            - auto format
            - code generate
            - code share

        - sexy shell (dot file/z script)
            - recompile/reactive
            - less thinking, do more
                - build
                - run test
                - config dev environment
              [demo]
            - stream commands for different tasks

        - a good test suit ([headless] browser)
            - cross browser
            - cover mobile platform

        - automation (dev/test/error-handle/build/deploy)
            - process

        all-in-one:
        - Yeoman：适合现代Web应用的现代工作流
        - branch.io: 
        - Metero
        - ef.io ? 

    6. Best practice from web.
        Google's javascript dev flow:
            Shell
                .  dotfile, `z` script, `server` alias
            Editor
                .  Learn it well, whatever it is
                .  More than any other tool, prioritize your familiarity with it
            Test
                .  code lint
                .  code quality / code coverage
                .  model/view/controller tests
            Realtime feedback
                . live linting 
                . live recompilation 
                . live reload
            Modules / Dependency Management
                . AMD modules 
                . CommonJS Modules 
                . ECMAScript Harmony modules 
                . Minispade require
            Dependency management tricks
                . Template Precompilation
                . Custom build output (has.js)
            In-browser Devtools
                . sourceURL
                . Source Maps
                . Navigating scripts
            Mobile
                . Test in Chrome
                . Emulators && Browser stack
                . Real devices & Adobe Shadow 
                . Chrome on Android w/ DevTools
            Build system
                . Resolve your dependency chain
                . concatenate/compile
                . Flatten your CSS @imports
                . Remove debugging statement
                . Compress images
                . Precompile templates
                . Run tests in a variety of environments
                . Revs asset paths for caching
                . Affirm code quality.
            Client-side error handling
                . window.onerror + http proxy
                . errorception
            Projects that hide the complexity
                . Grunt
                . LiveReload
                . Shadow
                . Brunch
                . WebStorm
            Future 
                . Code coverage realtime reports (webstorm)
                . stub out models/views with tests at the cmd line

    7. Useful resources 
        a.  Languages

             CSS:
             .  SASS/COMPASS
             HTML:
             .  HAML/Markdown
             JS:
             CoffeeScript/TypeScript/Dart
             Others:
             .  Ruby/Python/NodeJS

        b.  Tools

             Editor:
             .  Sublime Text 2/Apptana/Web Storm
             DevKit:
             .  Brunch.io/Yeoman(grunt)/LiverBoard/CodeKit
             
             xLints:
             . AutoLint/Sublime Linter/Closure Linter/Grunt
             . CSSLint/RECESS/Closure Stylesheets

             Testing:

             .  Travis CI/Jasmine/Qunit/Mocha/MockJax/HTMLDoc
             Documentation:

             .  JSDOC/KSS

             Productive Tools

             .   HotKey
             .   Alfred/Slick run
             .   UglifyJS/Closure Compiler
             .   OptiPNG/JPEGTran/pngquant

             Browser:

             .   Firefox Addon/Chorme extension/dotJS/SourceMaps
             .   phantomjs/casperjs

             Others:

             .  Gist for code snippets
             .  sourceURL/Source Map
             .  Command line

    8. Next share...

-->
