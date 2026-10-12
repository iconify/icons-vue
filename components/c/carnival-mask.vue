<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dnxf4qbve"/><path class="it7nrg50k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carnival-mask" /></template>
<style>
.dnxf4qbve {
  d: path("m12.38 3.08l1.24 1.09q.38.33 0 .66l-1.24 1.09q-.38.33-.76 0l-1.24-1.09q-.38-.33 0-.66l1.24-1.09q.38-.33.76 0M2.75 8.5c3-1 6.25-.75 9.25 1c3-1.75 6.25-2 9.25-1c0 4.5-2.25 7.25-5.25 7.25c-1.75 0-3-1-4-2.5c-1 1.5-2.25 2.5-4 2.5c-3 0-5.25-2.75-5.25-7.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it7nrg50k {
  d: path("M5.5 11.5c1.25-1.25 3-1.25 4.25 0c-1.25 1.25-3 1.25-4.25 0m8.75 0c1.25-1.25 3-1.25 4.25 0c-1.25 1.25-3 1.25-4.25 0m3.65 4.9l1.6 4.85");
}

</style>
