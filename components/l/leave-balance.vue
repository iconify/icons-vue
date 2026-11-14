<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm8rntbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leave-balance" /></template>
<style>
.nm8rntbps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 6.5h4.5a5.25 5.25 0 0 1 5.25 5.25v4.5a5.25 5.25 0 0 1-5.25 5.25h-4.5a5.25 5.25 0 0 1-5.25-5.25v-4.5A5.25 5.25 0 0 1 9.75 6.5m-1-4h6.5A1.75 1.75 0 0 1 17 4.25v.5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 4.75v-.5A1.75 1.75 0 0 1 8.75 2.5M4.5 13h15M8 16.25h.01m3.99 0h.01m3.99 0h.01M10 19h.01M14 19h.01");
}

</style>
