<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oqvcneb0y"/><rect class="tlg7vsbdb"/><path class="n582-rtxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:invitation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n582-rtxx {
  d: path("M2.75 11L12 16.75L21.25 11");
}

.oqvcneb0y {
  d: path("M6 10V4a1.25 1.25 0 0 1 1.25-1.25h9.5A1.25 1.25 0 0 1 18 4v6Z");
}

.tlg7vsbdb {
  width: 18.5px;
  height: 11.25px;
  x: 2.75px;
  y: 10px;
  rx: 2px;
}

</style>
