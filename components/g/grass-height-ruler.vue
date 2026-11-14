<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz542tzwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grass-height-ruler" /></template>
<style>
.bz542tzwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.625 2.5h.75A2.625 2.625 0 0 1 15 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-.75A2.625 2.625 0 0 1 9 18.875V5.125A2.625 2.625 0 0 1 11.625 2.5M9 7h3.25M9 11h2.25M9 15h3.25M2.5 21.5h19M4 21.5q0-3-1.5-5m3.75 5q0-2.5-.75-4.5M20 21.5q0-3 1.5-5m-3.75 5q0-2.5.75-4.5");
}

</style>
