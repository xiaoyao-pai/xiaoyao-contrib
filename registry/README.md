# 逍遥派成员注册表

> 每位成员安装 Skill 时自动注册到此目录
> 掌门可在此查看所有入派成员

## 文件格式

每个成员一个 JSON 文件：`XYP-xxxx.json`

```json
{
  "token": "XYP-xxxx",
  "skill_version": "0.0.x",
  "installed_at": "YYYY-MM-DD"
}
```

注意：注册信息不含真实身份（hostname 仅存本地和密卷）。
