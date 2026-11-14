<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiai2ebyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deep-learning" /></template>
<style>
.eiai2ebyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 7a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m0 10a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m7.5-10a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m0 10a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m7.5-5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M6.75 7h3m-3 10h3m-4-8.25l5 6.5m-5 0l5-6.5m3-.5l4 2.5m-4 5l4-2.5");
}

</style>
