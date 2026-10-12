<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsf1atbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ethernet" /></template>
<style>
.tsf1atbuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 4.75h14.5q1.5 0 1.5 1.5v8.25q0 1.5-1.5 1.5H17q-1.5 0-1.5 1.5v.75q0 1.5-1.5 1.5h-4q-1.5 0-1.5-1.5v-.75Q8.5 16 7 16H4.75q-1.5 0-1.5-1.5V6.25q0-1.5 1.5-1.5m2.75 3.5v3m3-3v3m3-3v3m3-3v3");
}

</style>
