<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lebwfgb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clean-air" /></template>
<style>
.lebwfgb9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.25h8.5A2.75 2.75 0 1 0 8.5 6.5m-5.75 6.75H17.5A2.75 2.75 0 1 1 14.75 16m-12 1.25h6M18 3q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25Q17.61 5.86 18 3");
}

</style>
