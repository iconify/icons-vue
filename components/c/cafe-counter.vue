<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w4kebubil"/><path class="v7cuadbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cafe-counter" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7cuadbon {
  d: path("M14 7h5v3.5a2.5 2.5 0 0 1-5 0Zm5 .5h1a1.25 1.25 0 0 1 0 2.5h-1");
}

.w4kebubil {
  d: path("M2.5 13h19v7.5h-19Zm1 0l1-5H10l1 5M5.25 4h4v4h-4Z");
}

</style>
