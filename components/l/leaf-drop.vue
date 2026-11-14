<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh5ep4hbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-drop" /></template>
<style>
.wh5ep4hbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5C10 3.5 16 6 17.75 11.75c-6 1-12.25-1.25-14.25-7.25m0 0l8 4.25m6.25 5.75S15 17 15 18.75a2.75 2.75 0 0 0 5.5 0c0-1.75-2.75-4.25-2.75-4.25");
}

</style>
