<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dnp2npbye"/><circle class="ukn7g3d-n"/><path class="iouialbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:easy-read" /></template>
<style>
.dnp2npbye {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iouialbut {
  d: path("m7.75 12.5l2-2l1.5 1.5l3-3.25l2.5 2.75M8 16h8m-8 2.5h5");
}

.ukn7g3d-n {
  cx: 8.75px;
  cy: 6.5px;
  r: 1.25px;
}

</style>
