<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr0vkvbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:espresso" /></template>
<style>
.kr0vkvbpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5h9v8a2.5 2.5 0 0 1-2.5 2.5H9A2.5 2.5 0 0 1 6.5 13Zm9 5.25h1a1.5 1.5 0 0 1 0 3h-1M3 15.5h18q-1.5 3-4.5 3h-9q-3 0-4.5-3m3.5-7.75h9");
}

</style>
