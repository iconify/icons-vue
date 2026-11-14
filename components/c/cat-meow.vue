<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxa8x7s5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cat-meow" /></template>
<style>
.sxa8x7s5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 14.5c0-3.25 1-5.25 2-6.25L5.75 3.5L9 6.25C10 6 11 6 12 6.5l1.5-2.75l.25 4.5q1.125 1.5 1.5 3L13 13l2.25 1.75C14.5 18 12.25 20 9.5 20C6.25 20 4 17.75 4 14.5m13.5-4.75a5.5 5.5 0 0 1 0 6.5M20 8a8.5 8.5 0 0 1 0 10M9.75 11h.01");
}

</style>
