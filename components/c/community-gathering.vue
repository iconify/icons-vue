<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwz7uubti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:community-gathering" /></template>
<style>
.vwz7uubti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M9.5 13c0-2 1-3.25 2.5-3.25S14.5 11 14.5 13M2.75 11.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M2 21c0-2.75 1.25-4.5 3-4.5s3 1.75 3 4.5m8.75-9.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M16 21c0-2.75 1.25-4.5 3-4.5s3 1.75 3 4.5");
}

</style>
