<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8gkheayb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-pressure-gauge" /></template>
<style>
.r8gkheayb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9a7 7 0 1 0 14 0A7 7 0 1 0 5 9Zm7 7v3m-9 0h18M3 22h18M12 9h.01M12 9l3-3M5 9h2.5M7 4l1.75 1.75M12 2v2.5");
}

</style>
