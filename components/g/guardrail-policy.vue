<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmlo9ccga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guardrail-policy" /></template>
<style>
.hmlo9ccga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 6h13.75A2.625 2.625 0 0 1 21.5 8.625v.25a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 8.875v-.25A2.625 2.625 0 0 1 5.125 6M6 3v3m0 5.5V20m9.5-17v3m0 5.5v3.8m-.75 2.7l2 2L21 15.75");
}

</style>
