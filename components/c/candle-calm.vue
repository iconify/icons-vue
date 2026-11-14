<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhy0rv_br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:candle-calm" /></template>
<style>
.nhy0rv_br {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.125 12.5h1.75a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-1.75A2.625 2.625 0 0 1 8.5 18.875v-3.75a2.625 2.625 0 0 1 2.625-2.625M12 2.5C10 5 9.5 6 9.5 7a2.5 2.5 0 0 0 5 0c0-1-.5-2-2.5-4.5");
}

</style>
