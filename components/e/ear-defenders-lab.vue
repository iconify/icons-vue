<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x39cyxoil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ear-defenders-lab" /></template>
<style>
.x39cyxoil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 10a6.5 6.5 0 0 1 13 0m-15 0h4a1 1 0 0 1 1 1v8.5a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1Zm13 0h4a1 1 0 0 1 1 1v8.5a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1Z");
}

</style>
