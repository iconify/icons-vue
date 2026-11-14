<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtefalbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:haptic-wristband" /></template>
<style>
.rtefalbxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7.5h9v9h-9Zm2.5 0v-5h4v5m-4 9v5h4v-5M5 9a4.5 4.5 0 0 0 0 6m14-6a4.5 4.5 0 0 1 0 6");
}

</style>
