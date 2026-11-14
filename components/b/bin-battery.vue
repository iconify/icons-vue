<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-kx2cq1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bin-battery" /></template>
<style>
.h-kx2cq1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.625 2.5h7.75A2.625 2.625 0 0 1 18 5.125v.75A2.625 2.625 0 0 1 15.375 8.5h-7.75A2.625 2.625 0 0 1 5 5.875v-.75A2.625 2.625 0 0 1 7.625 2.5m12.625 2v2M4 11.25h16m-14.5 0L7 21.5h10l1.5-10.25m-6.5 3v4.25");
}

</style>
