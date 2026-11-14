<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plsahmbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brush-set" /></template>
<style>
.plsahmbzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13h10a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18v-1.5A3.5 3.5 0 0 1 7 13m-.5 0V8.5M5 8.5C5 6.5 6.5 4 6.5 4S8 6.5 8 8.5Zm7 4.5V7m-1.5 0c0-2 1.5-4.5 1.5-4.5S13.5 5 13.5 7Zm7 6V8.5m-1.5 0c0-2 1.5-4.5 1.5-4.5S19 6.5 19 8.5Z");
}

</style>
