<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uff-8ymft"/><path class="g4va33b3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lesson" /></template>
<style>
.g4va33b3y {
  d: path("m11.1 7.27l2.8 1.71q.85.52 0 1.04l-2.8 1.71q-.85.52-.85-.48v-3.5q0-1 .85-.48M2.75 19.75h8m3.25 0h7.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uff-8ymft {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 3.25px;
  rx: 2.5px;
}

</style>
