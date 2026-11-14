<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4wl4g49j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:foot-measurement" /></template>
<style>
.k4wl4g49j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.5c3.5 0 4.5 3 4 6C12 15 11 16 11 18s-.5 3.5-2.5 3.5s-3-1.5-2.5-4S4 13 4 10c0-2 2-3.5 4.5-3.5M4.5 4h.01M8 3h.01m3.49 1h.01m3.99 14v3h3m-3 0l5.5-5.5m-3 0h3v3");
}

</style>
