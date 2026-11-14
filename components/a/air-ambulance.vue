<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esbq_ttjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-ambulance" /></template>
<style>
.esbq_ttjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 15v-2.5c0-2 2-3.5 4.5-3.5h6.5c2 0 3.5 1.5 3.5 3.5V15ZM19 11l2.5-1.5M4 4.5h16m-8 0V9m-6 9.5h11m-7.5-7.75v2.5M8.25 12h2.5");
}

</style>
