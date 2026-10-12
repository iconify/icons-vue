<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jigb1zuzr"/><path class="dwizbh6dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hoarding-panel" /></template>
<style>
.dwizbh6dz {
  d: path("M2.75 14h18.5M6.5 8h11m-11 2.75h7M5 17.25L8 14m1.5 3.25l3-3.25m1.5 3.25L17 14m1.5 3.25l2.75-3M6 17.25v4m12-4v4m-14 0h4m8 0h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jigb1zuzr {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 4.25px;
  rx: 1.5px;
}

</style>
