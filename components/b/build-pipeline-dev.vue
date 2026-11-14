<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_54xbcjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:build-pipeline-dev" /></template>
<style>
.q_54xbcjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 7.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm7 0h1.5m-3.25 3l.75 1.25M5.5 10.25l-.75 1.25m-1-4.25h-1.5m3.25-3L4.75 3M9 4.25L9.75 3m3.5 13.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm6.5 1.75l1.25.75m-4.25 1v1.5m-3-3.25l-1.25.75M13.75 15l-1.25-.75m4.25-1v-1.5m3 3.25l1.25-.75m-8.75-7h4.5v4.5");
}

</style>
