<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s5ongy7ox"/><path class="e70znug-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:average-speed-check" /></template>
<style>
.e70znug-y {
  d: path("M3.75 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M14.5 3H19a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 19 8h-4.5A2.5 2.5 0 0 1 12 5.5A2.5 2.5 0 0 1 14.5 3m4 5v13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s5ongy7ox {
  d: path("M2.5 15.75za1.68 1.68 0 0 1 1.197-1.609l.738-.221a1.75 1.75 0 0 0 .912-.647l1.129-1.552A1.75 1.75 0 0 1 7.891 11h2.718a1.75 1.75 0 0 1 1.415.721l1.146 1.575a1.75 1.75 0 0 0 .862.631l.593.198a1.645 1.645 0 0 1 1.125 1.561v.064A1.25 1.25 0 0 1 14.5 17H3.75a1.25 1.25 0 0 1-1.25-1.25");
}

</style>
