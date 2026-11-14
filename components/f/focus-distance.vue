<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_ugfnwgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:focus-distance" /></template>
<style>
.l_ugfnwgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h19M3 15v3.5M7.5 15v3.5M12 15v3.5m4.5-3.5v3.5M21 15v3.5m-13.5-9za.89.89 0 0 1 .782 1.317l-.032.058a.854.854 0 0 1-1.5 0l-.032-.058A.89.89 0 0 1 7.5 9.5M18 9c-1.25-2.5-3.5-2.5-3.5 0s2.25 2.5 3.5 0s3.5-2.5 3.5 0s-2.25 2.5-3.5 0");
}

</style>
