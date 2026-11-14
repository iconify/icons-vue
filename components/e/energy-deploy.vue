<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ka43k88xk"/><path class="y1v_xr-xm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-deploy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ka43k88xk {
  d: path("M7 5.5h3A3.5 3.5 0 0 1 13.5 9v7.5A3.5 3.5 0 0 1 10 20H7a3.5 3.5 0 0 1-3.5-3.5V9A3.5 3.5 0 0 1 7 5.5m-.5-2.75h4");
}

.y1v_xr-xm {
  d: path("m10 8.5l-3 4h3.5l-2.5 4m7 4.5l5.25-5.25m-4-.25h4.25v4.25");
}

</style>
