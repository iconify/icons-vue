<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9w9xcc_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:laser-hair-removal" /></template>
<style>
.t9w9xcc_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.889 12.111za2.5 2.5 0 0 1 0 3.535l-4.243 4.243a2.5 2.5 0 0 1-3.535 0a2.5 2.5 0 0 1 0-3.535l4.243-4.243a2.5 2.5 0 0 1 3.535 0M14 10l5-5m-7.25 2.75l5-5m-.5 9.5l5-5");
}

</style>
