<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvvib024d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:health-long-term-care" /></template>
<style>
.kvvib024d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5v16m0-4.5h17m0-3.5v8M8.125 12.25h1.75a1.875 1.875 0 0 1 1.875 1.875A1.875 1.875 0 0 1 9.875 16h-1.75a1.875 1.875 0 0 1-1.875-1.875a1.875 1.875 0 0 1 1.875-1.875M15 11l-3.25-3.25C11 6.5 11.75 4.5 13.5 4.5c.75 0 1.25.5 1.5 1c.25-.5.75-1 1.5-1c1.75 0 2.5 2 1.75 3.25Z");
}

</style>
