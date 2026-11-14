<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_k8kqb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boots-armour" /></template>
<style>
.u_k8kqb6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.5V3h9v3.5m-9 4V21h15v-4a3 3 0 0 0-2-2.75l-4-1.75v-2m-8.75-4h8.5A1.75 1.75 0 0 1 16 8.25v.5a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 4 8.75v-.5A1.75 1.75 0 0 1 5.75 6.5");
}

</style>
