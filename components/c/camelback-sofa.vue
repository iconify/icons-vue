<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mrdjpnb7x"/><path class="dy5rlwbrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camelback-sofa" /></template>
<style>
.dy5rlwbrl {
  d: path("M4.5 10V9c0-1.25 1.25-2 3-2c2 0 2.5-2.5 4.5-2.5S14.5 7 16.5 7c1.75 0 3 .75 3 2v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mrdjpnb7x {
  d: path("M2.5 12a2 2 0 0 1 4 0v2.5h11V12a2 2 0 0 1 4 0v5.5A1.5 1.5 0 0 1 20 19H4a1.5 1.5 0 0 1-1.5-1.5ZM5 19v1.5M19 19v1.5");
}

</style>
