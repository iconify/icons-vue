<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9vug6ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camp-table" /></template>
<style>
.w9vug6ber {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 8H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 5m1 3l5 11m0-11L5 19m9-11l5 11m0-11l-5 11");
}

</style>
