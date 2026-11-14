<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnpq88vtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaves-falling" /></template>
<style>
.vnpq88vtn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10q5.25-.75 5-6q-5.25.75-5 6m15 3q.75-4.25-3.5-5.5q-.75 4.25 3.5 5.5m-13 6q4.25 1.5 6.5-2.5Q8.75 15 6.5 19m-2-9L3 11.5M19.5 13l1 1.75M6.5 19l-1.75.75");
}

</style>
