<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ogmdmhbif"/><path class="xhh22682v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:food-container" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ogmdmhbif {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 5.75px;
  rx: 1.5px;
}

.xhh22682v {
  d: path("M5.25 9.75h13.5q1.5 0 1.32 1.49l-.89 7.52q-.18 1.49-1.68 1.49h-11q-1.5 0-1.68-1.49l-.89-7.52q-.18-1.49 1.32-1.49M7.5 14.5h9");
}

</style>
