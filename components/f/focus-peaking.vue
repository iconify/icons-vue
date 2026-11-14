<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qstaulysb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:focus-peaking" /></template>
<style>
.qstaulysb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5V5a2 2 0 0 1 2-2h2.5m9 0H19a2 2 0 0 1 2 2v2.5m0 9V19a2 2 0 0 1-2 2h-2.5m-9 0H5a2 2 0 0 1-2-2v-2.5M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

</style>
