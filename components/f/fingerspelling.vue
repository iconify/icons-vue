<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lum-f34ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fingerspelling" /></template>
<style>
.lum-f34ch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 13V6.5a1.5 1.5 0 0 1 3 0V4a1.5 1.5 0 0 1 3 0v.5a1.5 1.5 0 0 1 3 0v2a1.5 1.5 0 0 1 3 0v6c0 4-2 6.5-6 6.5s-6-2.5-6-6m3-6.5v3m3-5v5m3-3v3m3.25 12L18.5 15l2.75 6.5m-4.5-2.25h3.5");
}

</style>
