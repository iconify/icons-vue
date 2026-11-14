<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n18m6nbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:area-rectangle" /></template>
<style>
.n18m6nbnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3.5h8.25A2.625 2.625 0 0 1 16 6.125v6.25A2.625 2.625 0 0 1 13.375 15h-8.25A2.625 2.625 0 0 1 2.5 12.375v-6.25A2.625 2.625 0 0 1 5.125 3.5M4 17.75l-1.5 1.5l1.5 1.5m-1.5-1.5H16m-1.5-1.5l1.5 1.5l-1.5 1.5M18.75 5l1.5-1.5l1.5 1.5m-1.5-1.5V15m-1.5-1.5l1.5 1.5l1.5-1.5");
}

</style>
