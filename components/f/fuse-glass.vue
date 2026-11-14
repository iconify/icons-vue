<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g9ncjdw1m"/><path class="dyocuybui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fuse-glass" /></template>
<style>
.dyocuybui {
  d: path("M8.5 12C10 9.75 11 14.25 12 12s2 2.25 3.5 0");
}

.g9ncjdw1m {
  d: path("M8.5 8.5h7A3.5 3.5 0 0 1 19 12a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 12a3.5 3.5 0 0 1 3.5-3.5m-6 3.5H5m14 0h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
