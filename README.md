# intel
## intel
### intel
#### intel
...
    for(int i = 0; i<val; i++)
    {
        HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 1);   // LED On  1 = high
        HAL_Delay(200);     //HAL_Delay(1000) = 1000 ms = 1 sec
        HAL_GPIO_WritePin(LD2_GPIO_Port, LD2_Pin, 0);   // LED Off 0 = low
        HAL_Delay(200);
        flag=0;
    }
...
