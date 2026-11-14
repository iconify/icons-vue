<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h_qua6jtb"/><path class="yp3l3bcdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bucket-farm" /></template>
<style>
.h_qua6jtb {
  d: path("M4.5 9h15l-2 12h-11Zm0 0c0-7.5 15-7.5 15 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yp3l3bcdt {
  d: path("M5.5 15q2.25-1.75 4.5 0t4.25 0q2.25-1.75 4.25 0");
}

</style>
