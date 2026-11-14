<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqwj9pb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dry-shampoo" /></template>
<style>
.zqwj9pb1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9H11a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H8.5A3.5 3.5 0 0 1 5 18v-5.5A3.5 3.5 0 0 1 8.5 9M7 9l1.5-3H11l1.5 3M9.75 6V3.5h2.75m3.25 0h.01M19 3h.01M18 6.25h.01");
}

</style>
