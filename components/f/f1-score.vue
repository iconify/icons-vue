<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op7ertb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:f1-score" /></template>
<style>
.op7ertb9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5V20m-4.5 0h9M5.5 6h13m-16 7.5l3-7.5l3 7.5a3 3 0 0 1-6 0m13 0l3-7.5l3 7.5a3 3 0 0 1-6 0");
}

</style>
