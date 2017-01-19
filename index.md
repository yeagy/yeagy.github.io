#hello
I write software... primarily for the JVM. [Resume](https://yeagy.github.io/resume.html).

Here are some of my contributions to open source:
* [Better SQL Support](https://github.com/yeagy/bss) is a JDBC utility library. This grew from loathing how JDBC handles null columns and primitive types. Later expanded to a neat java 8 API around JDBC. Finally finished off with a simple ORM that fits my tastes, which is actually a distaste... for hibernate.

* [JAX-RS client generator](https://github.com/yeagy/jaxrs-client-gen) creates java source files from annotated resources. I made this to overcome the limitations of proxy based clients, while still having the convenience of not having to write them by hand. I even went to the trouble of learning how to write an [IntelliJ IDEA plug-in](https://github.com/yeagy/jaxrs-client-gen-idea-plugin).

* [Tagged Modular Configuration](https://github.com/yeagy/tmc) can combine many configuration files in JSON or YAML into a single configuration file, and use Jackson to map that directly to a POJO. Tags can also be specified to allow runtime overrides. I wrote this to beef up the standard Dropwizard configuration API.
