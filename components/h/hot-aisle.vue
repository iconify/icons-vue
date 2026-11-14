<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs1cx4b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-aisle" /></template>
<style>
.bs1cx4b8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.6 21.5H3.5v-19h12v7.3m-12-1.05h12m-12 6.5h8.1m-4.85-9.5h.01M6.75 12h.01M17 21.5c-2.25 0-3.5-1.5-3.5-3.25c0-2 2-3 2.5-4.75c1.5 1 2 2.25 2 3.25c.75-.5 1-1 1.25-1.5c.75 1 1.25 2 1.25 3c0 1.75-1.25 3.25-3.5 3.25Z");
}

</style>
