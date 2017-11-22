# xray4jconfig


The xray4jconfig git repository provides a way for xray4j users to use and share [xray4j](https://www.xray4j.com) configurations.

Information about xray4j configuration is available at
[xray4j](https://www.xray4j.com/gettingstarted) - Getting started page.


## 

To make use of any configuration present in this repository, copy the configuration folder over to the xray4j/agentconfig directory and specify the configuration name when you use the xray4j agent.

ex:-
```
java -javaagent:/opt/xray4j/agentlib/xray4j-agent.jar=**configname** com.fruit.App
```

If you would like to share the configuration you have created with other users, create a pull request.


## License

xray4jconfig repository is licensed under the MIT License

