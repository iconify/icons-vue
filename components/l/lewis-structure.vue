<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9pdg1b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lewis-structure" /></template>
<style>
.u9pdg1b9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11-11a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-4.25 8.25l5.5-5.5m-6.5 1.5h.01m2.49-2.5h.01");
}

</style>
