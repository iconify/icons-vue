<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_pehbzop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:candles-trio" /></template>
<style>
.q_pehbzop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12h4v9h-4ZM10 8.5h4V21h-4Zm6.5 5.5h4v7h-4Zm-11-4.75C4.25 8.5 4.1 7 5.5 5.5c1.4 1.5 1.25 3 0 3.75Zm6.5-3.5C10.75 5 10.6 3.5 12 2c1.4 1.5 1.25 3 0 3.75Zm6.5 5.5c-1.25-.75-1.4-2.25 0-3.75c1.4 1.5 1.25 3 0 3.75Z");
}

</style>
