<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yve_ag-tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drywall-saw" /></template>
<style>
.yve_ag-tw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 12.5l12-9l-1.25 3.75l-1-.75L17 10.25l-1-.75l-1.25 3.75l-1-.75l-2.25 3ZM10 14l-5 5m-1.5-1.5l3 3");
}

</style>
