<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg323ew4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:event-source" /></template>
<style>
.wg323ew4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3.5h8a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2a2 2 0 0 1 2-2m0 6.75h8a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2a2 2 0 0 1 2-2m0 6.75h8a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2a2 2 0 0 1 2-2m12.75-4.75h4.25M19 9.75l2.5 2.5l-2.5 2.5");
}

</style>
