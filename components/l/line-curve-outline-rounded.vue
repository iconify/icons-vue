<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikcr2y90l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-curve-outline-rounded" /></template>
<style>
.ikcr2y90l {
  fill: currentColor;
  d: path("M18.5 20q-.233 0-.376-.19t-.155-.448q-.046-2.71-1.118-5.085t-2.89-4.155t-4.232-2.874t-5.156-1.237q-.22-.011-.396-.154Q4 5.713 4 5.5t.168-.357t.382-.137q2.962.046 5.57 1.187t4.56 3.084t3.104 4.544t1.191 5.564q.006.252-.118.433T18.5 20");
}

</style>
