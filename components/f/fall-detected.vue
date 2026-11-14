<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjbjyrfyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fall-detected" /></template>
<style>
.tjbjyrfyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 7.25L10 13m0 0l-4 2.5L3.5 19m6.5-6l2.5 4l-1.5 3.5M13.75 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.5 3.75l4.75 1.5m-5.5-.5L8 7M2.5 21.5h19m-2.25-8l1.75-.75m-2.5 3.5l2 .25");
}

</style>
