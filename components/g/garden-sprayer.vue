<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncfglvbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-sprayer" /></template>
<style>
.ncfglvbqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12a5 4 0 0 1 10 0v7.5a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2Zm5-4V4M6 4h5m2.5 14H15a2 2 0 0 0 2-2v-6l1-2m2.75.25h.01m-.51-3h.01M17.5 5h.01");
}

</style>
