<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-wokcbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-long-term-care" /></template>
<style>
.u-wokcbtb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5v16m0-4.5h17m0-3.5v8M6.25 12.25h5.5V16h-5.5ZM15 11l-3.25-3.25C11 6.5 11.75 4.5 13.5 4.5c.75 0 1.25.5 1.5 1c.25-.5.75-1 1.5-1c1.75 0 2.5 2 1.75 3.25Z");
}

</style>
