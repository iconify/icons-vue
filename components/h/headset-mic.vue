<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqne81b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:headset-mic" /></template>
<style>
.vqne81b4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12v-.5a7 7 0 0 1 14 0v.5M5.5 12zA2.5 2.5 0 0 1 8 14.5V16a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 3 16v-1.5A2.5 2.5 0 0 1 5.5 12m13 0za2.5 2.5 0 0 1 2.5 2.5V16a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 16 16v-1.5a2.5 2.5 0 0 1 2.5-2.5m0 6.5v.5a2.5 2.5 0 0 1-2.5 2.5h-3.5");
}

</style>
