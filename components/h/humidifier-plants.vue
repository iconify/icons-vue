<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkkmpx34x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:humidifier-plants" /></template>
<style>
.xkkmpx34x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21v-8c0-2.5 1.5-3.5 3.25-3.5s3.25 1 3.25 3.5v8Zm12.271-6h3.958a1.5 1.5 0 0 1 1.48 1.747l-.5 3A1.5 1.5 0 0 1 18.729 21h-2.958a1.5 1.5 0 0 1-1.48-1.253l-.5-3A1.5 1.5 0 0 1 15.271 15m1.979 0V9.5m0 1.5c0-3-1.75-4.5-4.25-4.5c0 3 1.75 4.5 4.25 4.5m0-1.5c0-3 1.75-4.5 4.25-4.5c0 3-1.75 4.5-4.25 4.5m-11-3h.01M9.5 5h.01M6.5 3.25h.01");
}

</style>
