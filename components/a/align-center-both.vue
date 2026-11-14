<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl0e-vbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:align-center-both" /></template>
<style>
.rl0e-vbme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.625 6h6.75A2.625 2.625 0 0 1 18 8.625v6.75A2.625 2.625 0 0 1 15.375 18h-6.75A2.625 2.625 0 0 1 6 15.375v-6.75A2.625 2.625 0 0 1 8.625 6M12 2.5v19M2.5 12h19");
}

</style>
