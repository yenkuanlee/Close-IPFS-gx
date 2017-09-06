# Close-IPFS-gx
這個專案是配合 https://github.com/yenkuanlee/go-ipfs ( 封閉式 IPFS 專案 )

在編譯封閉式 IPFS 專案時候,

一定要將此專案的4個檔案上傳到官方的 IPFS,

才能成功編譯.

## 使用方法

```
  $ git clone https://github.com/yenkuanlee/Close-IPFS-gx
  $ cd Close-IPFS-gx
  $ ipfs add -r Qm*
```

## 編譯封閉式 IPFS 專案方法

```
  $ mkdir -p $GOPATH/github.com/ipfs
  $ cd $GOPATH/github.com/ipfs
  $ git clone https://github.com/yenkuanlee/go-ipfs --branch "feature/private-group-key"
  $ cd go-ipfs
  $ make install
```
