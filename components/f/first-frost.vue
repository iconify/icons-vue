<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1m5_dnjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:first-frost" /></template>
<style>
.i1m5_dnjz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.769 16.057C10.451 17.61 7.386 18.5 3.5 18.5c0-10 4.5-15 15-15c0 3.989-.991 7.537-3.128 10.18M2.5 19.5L12 10m6 5v6m-2.5-4.5l5 3m-5 0l5-3");
}

</style>
