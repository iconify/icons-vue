<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm1nx98xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cosmetic-spray" /></template>
<style>
.rm1nx98xg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 11h2.75a2.625 2.625 0 0 1 2.625 2.625v5.25A2.625 2.625 0 0 1 9.875 21.5h-2.75A2.625 2.625 0 0 1 4.5 18.875v-5.25A2.625 2.625 0 0 1 7.125 11M6.5 11V5.5A1.5 1.5 0 0 1 8 4h6.5v3.5h-4V11m2.25-3.5L15 11m3-8h.01m2.49 2.75h.01M18 8.5h.01");
}

</style>
