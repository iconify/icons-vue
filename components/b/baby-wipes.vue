<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w82h3w6cz"/><path class="i27qd70hi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-wipes" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i27qd70hi {
  d: path("M9.75 12.5h4.5A2.75 2.75 0 0 1 17 15.25A2.75 2.75 0 0 1 14.25 18h-4.5A2.75 2.75 0 0 1 7 15.25a2.75 2.75 0 0 1 2.75-2.75");
}

.w82h3w6cz {
  d: path("M7.75 9h8.5a5.25 5.25 0 0 1 5.25 5.25v2a5.25 5.25 0 0 1-5.25 5.25h-8.5a5.25 5.25 0 0 1-5.25-5.25v-2A5.25 5.25 0 0 1 7.75 9m.75 0l-1-6q2.5-1 4.5.5t4.5-.5l-1 6");
}

</style>
