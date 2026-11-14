<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd3wktk_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:borehole" /></template>
<style>
.wd3wktk_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 3h4.5A1.75 1.75 0 0 1 12 4.75a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 4 4.75A1.75 1.75 0 0 1 5.75 3M6 6.5V20m4-13.5V20m-7.5 0h10m6-7.5c-1.25 1.75-3 3.75-3 6a3 3 0 0 0 6 0c0-2.25-1.75-4.25-3-6");
}

</style>
