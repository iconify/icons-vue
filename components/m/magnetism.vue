<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9brrmc1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magnetism" /></template>
<style>
.k9brrmc1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 5h-4a7 7 0 0 0 0 14h4v-4.5h-4a2.5 2.5 0 0 1 0-5h4Zm3 3q2.5 4 0 8m3-10q3 6 0 12");
}

</style>
