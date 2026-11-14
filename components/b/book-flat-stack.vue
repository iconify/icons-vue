<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjsvf7r8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:book-flat-stack" /></template>
<style>
.qjsvf7r8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 15.5h12.75A2.625 2.625 0 0 1 21 18.125v.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-.75A2.625 2.625 0 0 1 5.625 15.5m2-6h9.75A2.625 2.625 0 0 1 20 12.125v.75a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 5 12.875v-.75A2.625 2.625 0 0 1 7.625 9.5m-1-6h8.75A2.625 2.625 0 0 1 18 6.125v.75A2.625 2.625 0 0 1 15.375 9.5h-8.75A2.625 2.625 0 0 1 4 6.875v-.75A2.625 2.625 0 0 1 6.625 3.5m-.125 12v6m10-12v6m-9-12v6");
}

</style>
