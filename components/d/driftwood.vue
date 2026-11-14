<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gs5npkbyz"/><path class="u0emlccut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:driftwood" /></template>
<style>
.gs5npkbyz {
  d: path("M3 9.5c4.5-1.5 8.5 0 11.5-1l2-4.5L19 5l-1.5 3.5c1.5-.25 2.75 0 3.5 1l-1 3l1 3c-4.5 1.25-8.5 0-12.5 1.25c-2 .5-4 .25-5.5-.5L4.25 13Z");
}

.u0emlccut {
  d: path("M7.75 12.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM4 20q2.5-1.25 5 0t5 0t5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
