<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz688e-vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lift-up" /></template>
<style>
.hz688e-vt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 2.5h4.75A2.625 2.625 0 0 1 12.5 5.125v12.25A2.625 2.625 0 0 1 9.875 20h-4.75A2.625 2.625 0 0 1 2.5 17.375V5.125A2.625 2.625 0 0 1 5.125 2.5m2.375 0V20m11 1V4m-3 3l3-3l3 3");
}

</style>
