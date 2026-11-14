<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6eiwobwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glue-dispenser" /></template>
<style>
.i6eiwobwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.5h2.5A1.75 1.75 0 0 1 15 4.25v6.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 10.75v-6.5a1.75 1.75 0 0 1 1.75-1.75m1.25 10za1.233 1.233 0 0 1 1.161 1.648l-.493 1.381A.71.71 0 0 1 12 16a.71.71 0 0 1-.668-.471l-.493-1.381A1.233 1.233 0 0 1 12 12.5m-9 8h18M7 5.5h2");
}

</style>
