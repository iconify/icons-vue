<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p60wh3eja"/><path class="nkygqyijr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:button-sensor" /></template>
<style>
.nkygqyijr {
  d: path("M7.5 13.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6.42-9.397a10 10 0 0 1 5.977 5.977M17 2.242A13 13 0 0 1 21.758 7");
}

.p60wh3eja {
  d: path("M3.5 13.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
