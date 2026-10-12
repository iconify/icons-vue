<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mrqc7nh_b"/><path class="j52lqni1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:backgammon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j52lqni1d {
  d: path("m5 4l1.75 6L8.5 4l1.75 6L12 4l1.75 6l1.75-6l1.75 6L19 4M5 20l1.75-6l1.75 6l1.75-6L12 20l1.75-6l1.75 6l1.75-6L19 20");
}

.mrqc7nh_b {
  width: 18.5px;
  height: 16px;
  x: 2.75px;
  y: 4px;
  rx: 2px;
}

</style>
