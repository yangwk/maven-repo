# maven-repo
个人maven仓库


# maven引入方法
##1、在项目pom.xml添加
<repositories>
	<repository>
		<id>yangwk-repo</id>
		<url>https://raw.githubusercontent.com/yangwk/maven-repo/master/repository</url>
	</repository>
</repositories>

##2、引入相关jar
例如：
<dependency>
	<groupId>com.github.yangwk</groupId>
	<artifactId>ydt-util</artifactId>
	<version>1.0</version>
</dependency>

