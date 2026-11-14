<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av66c5b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:interview-mic" /></template>
<style>
.av66c5b_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M3 21.5c0-4 3-6.25 6.5-6.25S16 17.5 16 21.5m3-18za1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 19 9.5a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 19 3.5m0 6v12");
}

</style>
