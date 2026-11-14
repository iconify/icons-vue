<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1q5p--ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:filter-minus" /></template>
<style>
.y1q5p--ef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.101 4h7.298a1.75 1.75 0 0 1 1.376 2.831l-2.901 3.693a1.75 1.75 0 0 0-.374 1.081v4.379a1.75 1.75 0 0 1-.882 1.52L10.75 18A1.17 1.17 0 0 1 9 16.984v-5.379a1.75 1.75 0 0 0-.374-1.081L5.725 6.831A1.75 1.75 0 0 1 7.101 4M15 18h6");
}

</style>
