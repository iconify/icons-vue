<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="laki4qb0l"/><path class="znpy08bhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-teller" /></template>
<style>
.laki4qb0l {
  d: path("M7 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-4 9.5c0-3 3-4.5 7-4.5c.664 0 1.301.041 1.901.124M2.5 15.5h10.1m-8.6 0v6h16V18m-5.5-5.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znpy08bhf {
  d: path("M17.25 9.75H19a2.75 2.75 0 0 1 0 5.5h-1.75");
}

</style>
