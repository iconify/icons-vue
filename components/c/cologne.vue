<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwgezibvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cologne" /></template>
<style>
.fwgezibvl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.125 9.5h7.75a2.625 2.625 0 0 1 2.625 2.625v6.25A2.625 2.625 0 0 1 15.875 21h-7.75A2.625 2.625 0 0 1 5.5 18.375v-6.25A2.625 2.625 0 0 1 8.125 9.5M11 7.5h2a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1a1 1 0 0 1 1-1m-1-4h4A1.5 1.5 0 0 1 15.5 5v1A1.5 1.5 0 0 1 14 7.5h-4A1.5 1.5 0 0 1 8.5 6V5A1.5 1.5 0 0 1 10 3.5M9 15.25h6");
}

</style>
