<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5fd5ou6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arnold-press" /></template>
<style>
.m5fd5ou6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5c0-3.75 4-6 8.5-6s8.5 2.25 8.5 6M9.25 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm-3 7V4.75M17.75 17V4.75M3.25 2.5V7m17.5-4.5V7M3.25 4.75h17.5");
}

</style>
