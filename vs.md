## spring-petclinic 在各版本JDK下的启动时间和内存占用比较

OpenJDK：

| 版本   | JDK17 | JDK21 | JDK24 | JDK25(EA) | Native Image |
|------|-------|-------|-------|-----------|--------------|
| 启动时间 | 4.45s | 4.34s | 3.99s | 2.98s     | 0.2s         |
| 内存占用 | 392MB | 446MB | 295MB | 265MB     | 103MB        |

OracleJDK：

| 版本   | JDK21 | JDK24 | Graal_CE24 |
|------|-------|-------|------------|
| 启动时间 | 3.98s | 3.95s | 3.39s      |
| 内存占用 | 280MB | 268MB | 308MB      |
