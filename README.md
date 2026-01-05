# protoc-gen-go-errors

将kratos框架的errors使用pkg/errors.WithStack (https://github.com/pkg/errors) 包裹，使error携带栈信息

### 使用方式

```bash
#将原来的kratos protoc-gen-go-errors
go install github.com/go-kratos/kratos/cmd/protoc-gen-go-errors/v2@latest

#替换为：
go install github.com/yvvlee/protoc-gen-go-errors@latest

```
