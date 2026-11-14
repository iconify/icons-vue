<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y235s8bcx"/><path class="en6lazoab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boxer-jab" /></template>
<style>
.en6lazoab {
  d: path("M9.5 12.5H14a3 3 0 0 1 3 3V19M2.5 6h4m-4 12h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y235s8bcx {
  d: path("M15.5 5za6 6 0 0 1 6 6v2a6 6 0 0 1-6 6a6 6 0 0 1-6-6v-2a6 6 0 0 1 6-6M7.25 9h.5a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 7.75 15h-.5a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 7.25 9");
}

</style>
