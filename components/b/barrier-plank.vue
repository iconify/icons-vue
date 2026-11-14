<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byie_xlod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barrier-plank" /></template>
<style>
.byie_xlod {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 5h13.75A2.625 2.625 0 0 1 21.5 7.625v1.75A2.625 2.625 0 0 1 18.875 12H5.125A2.625 2.625 0 0 1 2.5 9.375v-1.75A2.625 2.625 0 0 1 5.125 5m.375 7L3 20.5M5.5 12L8 20.5M18.5 12L16 20.5m2.5-8.5l2.5 8.5M6.5 12l3-7m2 7l3-7m2 7l3-7");
}

</style>
