<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv59vcoti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chess-bishop-outline" /></template>
<style>
.xv59vcoti {
  fill: currentColor;
  d: path("M5 21v-4.173q1.414-1.027 2.459-2.402t1.695-2.983H6.846v-1h2.012l-1.27-2.188q-.273-.46-.207-1.013q.065-.552.45-.937L12 2.019l4.17 4.285q.384.385.45.937q.064.553-.209 1.013l-1.269 2.188h1.993v1h-2.308q.67 1.608 1.714 2.983Q17.587 15.8 19 16.827V21zm1-1h12v-2.577q-1.442-1.2-2.516-2.7t-1.686-3.28h-3.59q-.612 1.76-1.689 3.26T6 17.404zm4.01-9.558h3.961l1.562-2.7q.096-.173.086-.375t-.163-.356L12 3.422l-3.456 3.59q-.154.154-.163.356t.086.375zm2.51-2.807q.21-.21.21-.52t-.21-.52t-.52-.21t-.52.21t-.21.52t.21.52q.21.211.52.211t.52-.21M12 3.42");
}

</style>
