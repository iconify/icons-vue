<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo2gz_bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:champagne" /></template>
<style>
.fo2gz_bdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.5h3V7c0 1.5 2.5 2.5 2.5 5v8a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 8 20v-8c0-2.5 2.5-3.5 2.5-5Zm0 3h3M8 14h8m-8 3.5h8M18.5 5a1 1 0 1 0 2 0a1 1 0 1 0-2 0m0 4.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
