
---

# uv\_handle\_t - Base handle

uv\_handle\_t 是所有 libuv 操作句柄种类的基础类。

结构是一致的，因此，任何 libuv  的操作句柄都可以被转换为 uv\_handle\_t 。所有的 API 函数被定义为可以和任何操作句柄类型进行工作。
