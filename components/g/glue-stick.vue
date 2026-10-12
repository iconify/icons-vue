<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-1xakbmf"/><rect class="d_g0gt48w"/><path class="kkv-xacei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glue-stick" /></template>
<style>
.d_g0gt48w {
  width: 10px;
  height: 12px;
  x: 7px;
  y: 9.25px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-1xakbmf {
  d: path("M9 9.25V6a3 3 0 0 1 6 0v3.25Z");
}

.kkv-xacei {
  d: path("M7 17.25h10");
}

</style>
