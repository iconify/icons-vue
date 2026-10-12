<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="r68nxu-oz"/><path class="prt16zu4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cross-dock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.prt16zu4x {
  d: path("M2.75 8h4M5 5.75L7.25 8L5 10.25M16.75 16h4.5M19 13.75L21.25 16L19 18.25");
}

.r68nxu-oz {
  width: 6.5px;
  height: 18.5px;
  x: 8.75px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
