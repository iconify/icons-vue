<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="qeablobnc"/><path class="b1toa9d5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lunar-eclipse" /></template>
<style>
.b1toa9d5u {
  d: path("M4.75 12.81a8.25 8.25 0 0 1 6.57-7.89a10.5 10.5 0 0 1-6.57 7.89m0 0a10.5 10.5 0 0 1-1.63.49m8.38-9.8a10.5 10.5 0 0 1-.18 1.42");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qeablobnc {
  cx: 13px;
  cy: 13px;
  r: 8.25px;
}

</style>
