<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rklnld8_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:claim-inspection" /></template>
<style>
.rklnld8_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.013 9.987l3.25-3.25a1.75 1.75 0 0 1 2.474 0l3.25 3.25a1.75 1.75 0 0 1 .513 1.238v5.025A1.75 1.75 0 0 1 10.75 18h-6.5a1.75 1.75 0 0 1-1.75-1.75v-5.025a1.75 1.75 0 0 1 .513-1.238M13 14.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m6 2.5l2 2");
}

</style>
