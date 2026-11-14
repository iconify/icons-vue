<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h99v-zbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chutney-jar" /></template>
<style>
.h99v-zbgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 10.5h5A5.5 5.5 0 0 1 20 16a5.5 5.5 0 0 1-5.5 5.5h-5A5.5 5.5 0 0 1 4 16a5.5 5.5 0 0 1 5.5-5.5m-2-3h9A1.5 1.5 0 0 1 18 9a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 9a1.5 1.5 0 0 1 1.5-1.5m-4-3.75h12.25m0 0a2.75 1.5 0 1 0 5.5 0a2.75 1.5 0 1 0-5.5 0");
}

</style>
