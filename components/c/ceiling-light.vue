<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tvlet40hx"/><rect class="gng0-vbwf"/><rect class="d5rsqe_ie"/><path class="apky6rb1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ceiling-light" /></template>
<style>
.apky6rb1r {
  d: path("M6.5 12h11a5.5 5 0 0 1-11 0");
}

.d5rsqe_ie {
  width: 15.5px;
  height: 4.75px;
  x: 4.25px;
  y: 7.25px;
  rx: 1.5px;
}

.gng0-vbwf {
  width: 6px;
  height: 2.75px;
  x: 9px;
  y: 4.5px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tvlet40hx {
  d: path("M2.75 4.5H9m6 0h6.25");
}

</style>
