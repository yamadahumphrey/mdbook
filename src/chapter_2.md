# chapter 2

and here is another pic:

![The Rust Logo](images/rustacean-orig-noshadow.png "The crab crab" =300x)

>test fdaasdf dsf asdf sadf sadf sad fsad fsad fsad fasdf dsafdsf sadf sadf sdaf 
adsfasdfdsaf  dsaf sdaf sadf dsf dsaf s fasf sdf sdf ds fsadf sadf sdf  
dsafsadf dsaf dsaf sadf sda fsd f sadf dsaf ds f dsaf
adfasdfsdf dasfsdfsdf

sdfdfsdf 
sdfsdf

hello again.

```dot process
digraph {
   "processed" -> "graph"
}
digraph G { 
  rankdir = TB;
  subgraph {
    A -> C
    A -> D
    B -> C
    B -> D
    A -> B
    C -> D
    // note that rank is used in the subgraph
    {rank = same; A; B;}
    {rank = same; C; D;}
  } /* closing subgraph */
}


graph test {
  甲 -- 丙
  甲 -- 丁
  乙 -- 丙
  乙 -- 丁
  甲 -- 乙
  丙 -- 丁
  {rank = same; 甲;乙;}
  {rank = same; 丙;丁;}
}
```
