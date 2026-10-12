<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gw-lz5rdd"/><circle class="xhptglb4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crypto-mining" /></template>
<style>
.gw-lz5rdd {
  d: path("m7.3 19.69l8.24-13.12M9.5 4.25Q19.93-.42 20.25 11Q16.2 5.51 9.5 4.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhptglb4e {
  cx: 17px;
  cy: 17px;
  r: 3.75px;
}

</style>
