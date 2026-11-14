<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8f0qrbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:days-of-week" /></template>
<style>
.n8f0qrbsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 4h10.25A4.375 4.375 0 0 1 21.5 8.375v7.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 16.125v-7.75A4.375 4.375 0 0 1 6.875 4M2.5 9h19m-14-6.5V6m9-3.5V6M5 13.5v2m2.5-1h.01m2.24 0h.01m2.24 0h.01m2.24 0h.01m2.24 0h.01m2.24 0h.01");
}

</style>
