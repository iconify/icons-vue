<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm9xlpudv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kidneys" /></template>
<style>
.dm9xlpudv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 5c-3.25 0-5.5 3.25-5.5 7s2.25 7 5.5 7c2 0 3-1.25 2.5-3c-.4-1.25-1.75-2.25-1.75-4s1.35-2.75 1.75-4C11 6.25 10 5 8 5m8 0c3.25 0 5.5 3.25 5.5 7s-2.25 7-5.5 7c-2 0-3-1.25-2.5-3c.4-1.25 1.75-2.25 1.75-4S13.9 9.25 13.5 8C13 6.25 14 5 16 5");
}

</style>
