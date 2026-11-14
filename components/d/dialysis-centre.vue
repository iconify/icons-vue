<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5127szzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dialysis-centre" /></template>
<style>
.v5127szzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.5c-4 0-6 4-6 8c0 4.5 2.5 8 6.5 8c3.5 0 5-2.5 3.75-4.5c-1-1.5-1-4.5 0-6c1.25-2-.5-5.5-4.25-5.5m9.5-3c1.5 2 2.25 3.25 2.25 4.25a2.25 2.25 0 0 1-4.5 0c0-1 .75-2.25 2.25-4.25");
}

</style>
