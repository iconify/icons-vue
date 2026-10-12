<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmd3g469v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bow-arrow" /></template>
<style>
.mmd3g469v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5q11 0 11 11m-11-11l11 11M6 18L17.5 6.5M6 18H3.5M6 18v2.5M20.54 3.81l-1.48 3.98q-.21.56-.63.14l-2.36-2.36q-.42-.42.14-.63l3.98-1.48q.56-.21.35.35");
}

</style>
