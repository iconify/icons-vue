<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x71yrbcsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:experiment-queue" /></template>
<style>
.x71yrbcsx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 4.5za1 1 0 0 1 1 1v3.367a1.5 1.5 0 0 0 .023.264l.912 5.105A1.5 1.5 0 0 1 5.208 16h-.916a1.5 1.5 0 0 1-1.477-1.764l.912-5.105a1.5 1.5 0 0 0 .023-.264V5.5a1 1 0 0 1 1-1m7.25 0za1 1 0 0 1 1 1v3.367a1.5 1.5 0 0 0 .023.264l.912 5.105A1.5 1.5 0 0 1 12.458 16h-.916a1.5 1.5 0 0 1-1.477-1.764l.912-5.105A1.5 1.5 0 0 0 11 8.867V5.5a1 1 0 0 1 1-1m7.25 0za1 1 0 0 1 1 1v3.367a1.5 1.5 0 0 0 .023.264l.912 5.105A1.5 1.5 0 0 1 19.708 16h-.916a1.5 1.5 0 0 1-1.477-1.764l.912-5.105a1.5 1.5 0 0 0 .023-.264V5.5a1 1 0 0 1 1-1M2.5 19.5h19");
}

</style>
