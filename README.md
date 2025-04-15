# -以下均在Sepolia测试网上进行
首先为您的账号铸造sepolia weth，其地址为：0xdd13E55209Fd76AfE204dBda4007C227904f0a81
我们内部铸造的稳定币地址为：0xc60FB9B3f9498A0Aca5eeCA0c1291a753B9d5699
质押借贷合约的地址为：0xa7Cc55e8A5799F053db78a3e47704F0301090453
调用mint函数使用sepolia eth铸造0.1个sepolia weth
![image](https://github.com/user-attachments/assets/0247773c-e6ee-4a8a-a36e-0b0bcc64eca9)
![image](https://github.com/user-attachments/assets/30c68eff-ffbf-4a28-b863-b2cbb881cb1f)
![image](https://github.com/user-attachments/assets/87e0dad7-2cc6-446c-be4e-5c4780ccfcb8)
![image](https://github.com/user-attachments/assets/997cf885-66cc-487c-8240-247dbc947e3a)

然后调用approve函数准许质押借贷合约转移您的weth数量
![image](https://github.com/user-attachments/assets/dc822f7a-8aa9-4573-ae23-341f9b428a12)
![image](https://github.com/user-attachments/assets/9257cc5a-fe2c-402b-9bd1-9a1f4cb4509a)

第二步调用质押借贷合约的depositCollateral输入要存入的sepolia weth数量
![image](https://github.com/user-attachments/assets/b7efd69c-bc7b-4e24-b5ba-b0bd2b133d25)
可以调用getAccountInformation获取您借出(铸造稳定币的数量)和与您weth质押物等价的稳定币的数量
![image](https://github.com/user-attachments/assets/edbd52f0-bb56-4ec8-8ad9-3d972ef7f57a)
![image](https://github.com/user-attachments/assets/3e538266-0907-424c-b639-0bf3d5a305c9)
![image](https://github.com/user-attachments/assets/325f9683-cf36-408e-b4a6-96d456b73373)

在此质押借贷的合约中的借贷阈值是50%，所以最多只能铸造(借走)质押物一半数量的稳定币，基于此例就是16.4稳定币的一半
就是8.2稳定币，接下来铸造6个稳定币为例
![image](https://github.com/user-attachments/assets/5510ae32-eabc-49b9-a146-503b15cc0582)
![image](https://github.com/user-attachments/assets/f2ab45d3-b93f-43ac-9311-14134429613e)
![image](https://github.com/user-attachments/assets/cfe1d4e1-0e9a-49d1-9dd1-b37f76098b87)
![image](https://github.com/user-attachments/assets/45aed797-0343-4e22-8874-09020239ed66)
