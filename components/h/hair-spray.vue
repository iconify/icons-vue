<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z94iv-bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hair-spray" /></template>
<style>
.z94iv-bas {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8.5h2A3.5 3.5 0 0 1 13 12v6a3.5 3.5 0 0 1-3.5 3.5h-2A3.5 3.5 0 0 1 4 18v-6a3.5 3.5 0 0 1 3.5-3.5m0-4h2a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 9.5 8.5h-2a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 7.5 4.5m8 2h5m-5-3l4-1.5m-4 7.5l4 1.5");
}

</style>
