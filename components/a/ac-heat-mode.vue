<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iehxlzb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ac-heat-mode" /></template>
<style>
.iehxlzb1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4-9.5V5m0 14v2.5M2.5 12H5m14 0h2.5M5.25 5.25L7 7m10 10l1.75 1.75m0-13.5L17 7M5.25 18.75L7 17");
}

</style>
