# mvn-repo
maven仓库
### 引入项目包

基于GitHub创建的个人Maven仓库

#### Maven

##### pom.xml

```xml

<repositories>
    <!-- github -->
    <repository>
        <id>github</id>
        <!-- https://raw.github.com/用户名/仓库名/分支名 -->
        <url>https://raw.github.com/xuzhou-99/mvn-repo/main</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```
