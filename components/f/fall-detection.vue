<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdl7isbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fall-detection" /></template>
<style>
.zdl7isbng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 5.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m.25 1.25l-7.25 5m2-8.5l2.75 5.25L19 11.5M3.5 16l5-4.5l-1.5 8m11-5V18m0 3h.01");
}

</style>
