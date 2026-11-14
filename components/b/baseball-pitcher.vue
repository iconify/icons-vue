<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm5yq17cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baseball-pitcher" /></template>
<style>
.bm5yq17cm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M6 21.5l4.5-7l6 7M9.25 8.75l1.25 5.75M4 12l5.5-2.5l5-3.5m2.75-1.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
