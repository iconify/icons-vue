<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er0ds-bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-fountain" /></template>
<style>
.er0ds-bew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16h18c0 3-2.5 5-5.5 5h-7c-3 0-5.5-2-5.5-5m9-3.5V16M7 9.5h10c0 2-2 3-5 3s-5-1-5-3m5 0v-6m-4 3q1-3 4-3t4 3");
}

</style>
