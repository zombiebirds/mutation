# mutation
function mutation(arr) {
  // 请把你的代码写在这里
  var n0 = arr[0].toLowerCase();
  var n1 = arr[1].toLowerCase();
  for(i=0;i<n1.length;i++){
   if(n0.indexOf(n1[i],0) == -1) {
     return false;
   }
  }return true;
  
}

mutation(["hello", "hey"]);
