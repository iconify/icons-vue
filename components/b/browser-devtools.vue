<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ox4hr5-lh"/><path class="t3267derh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:browser-devtools" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ox4hr5-lh {
  d: path("M7.75 3h8.5a5.25 5.25 0 0 1 5.25 5.25v7.5A5.25 5.25 0 0 1 16.25 21h-8.5a5.25 5.25 0 0 1-5.25-5.25v-7.5A5.25 5.25 0 0 1 7.75 3M2.5 8h19M6 5.5h.01M9 5.5h.01");
}

.t3267derh {
  d: path("M11.341 11.827za.564.564 0 0 1 .563-.522h.192a.564.564 0 0 1 .563.522a.99.99 0 0 0 .492.784l.126.073a.99.99 0 0 0 .925.034a.564.564 0 0 1 .733.226l.096.167a.564.564 0 0 1-.171.748a.99.99 0 0 0-.432.818v.146a.99.99 0 0 0 .432.818a.564.564 0 0 1 .171.748l-.096.167a.564.564 0 0 1-.733.226a.99.99 0 0 0-.925.034l-.126.073a.99.99 0 0 0-.492.784a.564.564 0 0 1-.563.522h-.192a.564.564 0 0 1-.563-.522a.99.99 0 0 0-.492-.784l-.126-.073a.99.99 0 0 0-.925-.034a.564.564 0 0 1-.733-.226l-.096-.167a.564.564 0 0 1 .171-.748a.99.99 0 0 0 .432-.818v-.146a.99.99 0 0 0-.432-.818a.564.564 0 0 1-.171-.748l.096-.167a.564.564 0 0 1 .733-.226a.99.99 0 0 0 .925-.034l.126-.073a.99.99 0 0 0 .492-.784");
}

</style>
