<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-cs4yvnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-cursor" /></template>
<style>
.n-cs4yvnu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8.61v8.325a1.115 1.115 0 0 0 1.875.815l.519-.485a1.5 1.5 0 0 1 2.31.325l1.384 2.306a1.33 1.33 0 0 0 1.787.479a1.245 1.245 0 0 0 .463-1.729l-1.121-1.867a1.5 1.5 0 0 1 1.137-2.264l.146-.015a1.02 1.02 0 0 0 .534-1.814l-6.6-5.25A1.5 1.5 0 0 0 5 8.61m13.125-3.985l.139.324a1.5 1.5 0 0 0 .787.787l.324.139a.408.408 0 0 1 0 .75l-.324.139a1.5 1.5 0 0 0-.787.787l-.139.324a.408.408 0 0 1-.75 0l-.139-.324a1.5 1.5 0 0 0-.787-.787l-.324-.139a.408.408 0 0 1 0-.75l.324-.139a1.5 1.5 0 0 0 .787-.787l.139-.324a.408.408 0 0 1 .75 0");
}

</style>
