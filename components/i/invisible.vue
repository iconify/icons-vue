<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb6tmvb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:invisible" /></template>
<style>
.zb6tmvb3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.603 11.58A10 10 0 0 1 4.34 8.572m5.014-3.215q.45-.124.91-.205m3.472 0a10 10 0 0 1 4 1.656m1.924 1.764a10 10 0 0 1 1.737 3.008m0 .84a10 10 0 0 1-1.737 3.008m-5.014 3.215q-.45.124-.91.205m-3.472 0a10 10 0 0 1-4-1.656M4.34 15.428a10 10 0 0 1-1.737-3.008M3.5 3.5l17 17");
}

</style>
