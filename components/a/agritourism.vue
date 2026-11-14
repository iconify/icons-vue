<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj_h17xae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:agritourism" /></template>
<style>
.cj_h17xae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5v6M6 13v8.5m-1-13h10.379a1.5 1.5 0 0 1 1.06.439l.75.75a1.5 1.5 0 0 1 0 2.122l-.75.75a1.5 1.5 0 0 1-1.06.439H5a1.5 1.5 0 0 1-1.5-1.5V10A1.5 1.5 0 0 1 5 8.5m2.423-5.526l.827.276a.791.791 0 0 1 0 1.5l-.827.276A1.08 1.08 0 0 1 6 4a1.08 1.08 0 0 1 1.423-1.026M18.75 17c-1.5-1.25-3.5-.5-3.5 1.75c0 2 1.75 3.5 3.5 2.75c1.75.75 3.25-.75 3.25-2.75c0-2.25-1.75-3-3.25-1.75m0 0l.75-1.75");
}

</style>
