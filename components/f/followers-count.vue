<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9xyftbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:followers-count" /></template>
<style>
.w9xyftbdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M6 21.5c0-4 2.75-6.5 6-6.5s6 2.5 6 6.5M6.25 7.25a2.5 2.5 0 1 0 0 4.5m11.5-4.5a2.5 2.5 0 1 1 0 4.5M2.5 20c0-3.25 1-5 3-5.5m16 5.5c0-3.25-1-5-3-5.5");
}

</style>
