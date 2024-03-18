solc 命令

//yarn solcjs --bin --abi --include-path node_moudle/ --base-path . -o . SimpleStorage.sol

--bin 编译二进制文件
--abi 编译 abi 文件
--include-path node_moudle 先要 node_moudle 里包含的所有文件和合约
--base-path . (.)代表现在这个文件夹
-o . 表示编译出来的二进制文件和 abi 文件也输出到现在这个文件夹
SimpleStorage.sol 表示要编译的文件
