<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfhk3obrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ferry-route" /></template>
<style>
.lfhk3obrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10.5h17l-2 4.5h-13Zm5.25-6h4.5A1.75 1.75 0 0 1 15 6.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 7 8.75v-2.5A1.75 1.75 0 0 1 8.75 4.5m-6.25 15H6m3 0h4m3 0h5.5");
}

</style>
