<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gbp15zb4d"/><rect class="ustt3lb1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cross-latin" /></template>
<style>
.gbp15zb4d {
  d: path("M10.75 2.75h2.5q.75 0 .75.75v1.25q0 .75.75.75h3.5q.75 0 .75.75v2.5q0 .75-.75.75h-3.5q-.75 0-.75.75v4.25q0 .75-.75.75h-2.5q-.75 0-.75-.75v-4.25q0-.75-.75-.75h-3.5Q5 9.5 5 8.75v-2.5q0-.75.75-.75h3.5q.75 0 .75-.75V3.5q0-.75.75-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ustt3lb1k {
  width: 11px;
  height: 3px;
  x: 6.5px;
  y: 18.25px;
  rx: 1px;
}

</style>
