<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa2sftbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-shampoo" /></template>
<style>
.xa2sftbac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9.5h2A3.5 3.5 0 0 1 14 13v5a3.5 3.5 0 0 1-3.5 3.5h-2A3.5 3.5 0 0 1 5 18v-5a3.5 3.5 0 0 1 3.5-3.5m.25-4h1.5A1.75 1.75 0 0 1 12 7.25v.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 7 7.75v-.5A1.75 1.75 0 0 1 8.75 5.5m6-.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
