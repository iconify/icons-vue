<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh07xb7gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:analytics-cohort-table" /></template>
<style>
.eh07xb7gu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3h14.5A1.75 1.75 0 0 1 21 4.75v2.5A1.75 1.75 0 0 1 19.25 9h-2.5A1.75 1.75 0 0 0 15 10.75v2.5A1.75 1.75 0 0 1 13.25 15h-2.5A1.75 1.75 0 0 0 9 16.75v2.5A1.75 1.75 0 0 1 7.25 21h-2.5A1.75 1.75 0 0 1 3 19.25V4.75A1.75 1.75 0 0 1 4.75 3M3 9h12M3 15h6M9 3v12m6-12v6");
}

</style>
