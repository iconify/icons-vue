<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8em4j52c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gift-box-lid" /></template>
<style>
.d8em4j52c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 11.5h10.75A2.625 2.625 0 0 1 20 14.125v4.75a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 18.875v-4.75A2.625 2.625 0 0 1 6.625 11.5M4.064 5.872l15.264-2.691A1.75 1.75 0 0 1 21.356 4.6a1.75 1.75 0 0 1-1.42 2.028L4.672 9.319A1.75 1.75 0 0 1 2.644 7.9a1.75 1.75 0 0 1 1.42-2.028M12 11.5v10m-.304-16.973l.608 3.446");
}

</style>
