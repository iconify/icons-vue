<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2wanob1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bedroom-count" /></template>
<style>
.y2wanob1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5.5v15M3 17h11.6M3 12.5h10.8M7 9.5h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 9 12.5H7A1.5 1.5 0 0 1 5.5 11A1.5 1.5 0 0 1 7 9.5m8.75 5h4.5l-2.75 3c1.75-.25 3.25.75 3.25 2S19.5 21.75 18 21.75c-1.25 0-2.25-.5-2.75-1.25");
}

</style>
