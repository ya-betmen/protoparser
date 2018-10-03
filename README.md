ProtoParser
===========

Java parser for `.proto` schema declarations.

`ProtoParser` will parse a standalone `File` or schema data directly and return an object
representation as a `ProtoFile` instance.

Original project is depricated! But wire-schema (https://github.com/square/wire/) is too big and inconvenient.

Download
--------

Download [the latest .jar][dl] or depend via Maven: (not working yet)
```xml
<dependency>
  <groupId>io.github.ya-betmen</groupId>
  <artifactId>protoparser</artifactId>
  <version>4.0.5</version>
</dependency>
```

Snapshots of the development version are available in [Sonatype's `snapshots` repository][snap].

License
-------

    Copyright 2013 Square, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.



 [dl]: https://search.maven.org/remote_content?g=io.github.ya-betmen&a=protoparser&v=LATEST
 [snap]: https://oss.sonatype.org/content/repositories/snapshots/
