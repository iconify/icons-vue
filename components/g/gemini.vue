<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bair65p_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gemini" /></template>
<style>
.bair65p_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 4c5 1.75 10.5 1.75 15.5 0M4.25 20c5-1.75 10.5-1.75 15.5 0M8.5 5.25v13.5m7-13.5v13.5");
}

</style>
