## java archetype
maven项目的java初始化模板

### 1. 编译到本地

```bash
mvn clean install
```

### 2. 使用archetype

```bash
mvn archetype:generate                                  \
  -DarchetypeGroupId=com.whiteclaw.archetypes            \
  -DarchetypeArtifactId=java-archetype         \
  -DarchetypeVersion=1.0                \
  -DgroupId=projectGroupId                          \
  -DartifactId=projectArtifactId
    
```