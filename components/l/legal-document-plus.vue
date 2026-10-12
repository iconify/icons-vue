<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><path class="rzzh4ie6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:legal-document-plus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rzzh4ie6d {
  d: path("M13.75 6.75c-.35-.65-.95-1-1.75-1c-1 0-1.75.6-1.75 1.4c0 1.95 3.5 1.75 3.5 3.7m-3.5 3.4c.35.65.95 1 1.75 1c1 0 1.75-.6 1.75-1.4c0-1.95-3.5-1.75-3.5-3.7m-1.75 8.1h7");
}

.x00qgzx7x {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
