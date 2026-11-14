<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgx3bkbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hierarchy" /></template>
<style>
.kgx3bkbsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 2.5h1A2.5 2.5 0 0 1 15 5a2.5 2.5 0 0 1-2.5 2.5h-1A2.5 2.5 0 0 1 9 5a2.5 2.5 0 0 1 2.5-2.5m-6 14h1A2.5 2.5 0 0 1 9 19a2.5 2.5 0 0 1-2.5 2.5h-1A2.5 2.5 0 0 1 3 19a2.5 2.5 0 0 1 2.5-2.5m12 0h1A2.5 2.5 0 0 1 21 19a2.5 2.5 0 0 1-2.5 2.5h-1A2.5 2.5 0 0 1 15 19a2.5 2.5 0 0 1 2.5-2.5m-5.5-9V12m-6 4.5v-3A1.5 1.5 0 0 1 7.5 12h9a1.5 1.5 0 0 1 1.5 1.5v3");
}

</style>
