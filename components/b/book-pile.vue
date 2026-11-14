<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8t_dacjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:book-pile" /></template>
<style>
.l8t_dacjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 15.5h12.75A2.625 2.625 0 0 1 21 18.125v.25A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375v-.25A2.625 2.625 0 0 1 5.625 15.5m1.5-5.5h10.25A2.625 2.625 0 0 1 20 12.625v.25a2.625 2.625 0 0 1-2.625 2.625H7.125A2.625 2.625 0 0 1 4.5 12.875v-.25A2.625 2.625 0 0 1 7.125 10m.474-5.965l8.417-1.183a2.25 2.25 0 0 1 2.541 1.915a2.25 2.25 0 0 1-1.915 2.541L8.225 8.491a2.25 2.25 0 0 1-2.541-1.915a2.25 2.25 0 0 1 1.915-2.541M17 18.25h4m-16.5-5.5h4");
}

</style>
