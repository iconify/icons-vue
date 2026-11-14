<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9nnfgl7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-range-bar" /></template>
<style>
.j9nnfgl7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h19M4.5 9zA1.5 1.5 0 0 1 6 10.5V15a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 3 15v-4.5A1.5 1.5 0 0 1 4.5 9m5-5.5zA1.5 1.5 0 0 1 11 5v6.5A1.5 1.5 0 0 1 9.5 13A1.5 1.5 0 0 1 8 11.5V5a1.5 1.5 0 0 1 1.5-1.5m5 4zA1.5 1.5 0 0 1 16 9v7.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5V9a1.5 1.5 0 0 1 1.5-1.5m5-5zA1.5 1.5 0 0 1 21 4v5a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 18 9V4a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
