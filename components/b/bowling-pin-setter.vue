<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlqak3bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bowling-pin-setter" /></template>
<style>
.xlqak3bem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 2.5h12.75A2.625 2.625 0 0 1 21 5.125v.25A2.625 2.625 0 0 1 18.375 8H5.625A2.625 2.625 0 0 1 3 5.375v-.25A2.625 2.625 0 0 1 5.625 2.5M8 8v3m8-3v3m-9.25 9.5h2.5c1.25-2 1-4.25-.5-6c.75-.75.75-1.5.75-2a1.5 1.5 0 0 0-3 0c0 .5 0 1.25.75 2c-1.5 1.75-1.75 4-.5 6m8 0h2.5c1.25-2 1-4.25-.5-6c.75-.75.75-1.5.75-2a1.5 1.5 0 0 0-3 0c0 .5 0 1.25.75 2c-1.5 1.75-1.75 4-.5 6");
}

</style>
