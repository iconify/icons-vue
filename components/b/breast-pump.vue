<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr8i23ntx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breast-pump" /></template>
<style>
.gr8i23ntx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.625 11.5h2.75A2.625 2.625 0 0 1 14 14.125v4.75a2.625 2.625 0 0 1-2.625 2.625h-2.75A2.625 2.625 0 0 1 6 18.875v-4.75A2.625 2.625 0 0 1 8.625 11.5M8.25 9h3.5A1.25 1.25 0 0 1 13 10.25a1.25 1.25 0 0 1-1.25 1.25h-3.5A1.25 1.25 0 0 1 7 10.25A1.25 1.25 0 0 1 8.25 9m.25 0q-2.25-2.25-6-2.25V2.5c3.75 0 7.25 2.25 9.25 6.5M14 14q4.5 0 6 3v4.5");
}

</style>
