<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj30euugl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:greek-vase" /></template>
<style>
.vj30euugl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4h14c0 2-3 3-3 5c2.5 1.5 3 4 2 6.5c-1 2-3.5 3-4 3.5v1.5h-4V19c-.5-.5-3-1.5-4-3.5c-1-2.5-.5-5 2-6.5c0-2-3-3-3-5m3.5 9.5h7");
}

</style>
