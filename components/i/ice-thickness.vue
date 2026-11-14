<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjuzei2en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ice-thickness" /></template>
<style>
.pjuzei2en {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 4.5h7.25A2.625 2.625 0 0 1 15 7.125v3.75a2.625 2.625 0 0 1-2.625 2.625h-7.25A2.625 2.625 0 0 1 2.5 10.875v-3.75A2.625 2.625 0 0 1 5.125 4.5m14.375 0v9m-1.5-9h3M18 9h3m-3 4.5h3M2.5 18q2.25-1.5 4.75 0Q9.5 19.5 12 18q2.25-1.5 4.75 0q2.25 1.5 4.75 0");
}

</style>
