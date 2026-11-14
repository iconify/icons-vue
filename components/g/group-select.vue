<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1e1nmb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:group-select" /></template>
<style>
.l1e1nmb3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v2a2.5 2.5 0 0 1-2.5 2.5h-2m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2m5.25-9h.5A1.75 1.75 0 0 1 11 8.75v.5A1.75 1.75 0 0 1 9.25 11h-.5A1.75 1.75 0 0 1 7 9.25v-.5A1.75 1.75 0 0 1 8.75 7m3.75 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
