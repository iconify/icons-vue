<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rogey3bnw"/><path class="jxyddgrou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:backpack-travel" /></template>
<style>
.jxyddgrou {
  d: path("M8 21.5V16a1.5 1.5 0 0 1 1.5-1.5h5A1.5 1.5 0 0 1 16 16v5.5");
}

.rogey3bnw {
  d: path("M5 21.5V10a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v11.5ZM10 5V3.5h4V5m-9 6h14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
