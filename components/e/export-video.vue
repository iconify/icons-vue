<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qi4hhgzkb"/><path class="kfo4_wcff"/><path class="ad6-v8gsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:export-video" /></template>
<style>
.ad6-v8gsc {
  d: path("M12 18.75v-4.5M9.75 16.5L12 14.25l2.25 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfo4_wcff {
  d: path("m12.065 6.033l.185.092a.978.978 0 0 1 0 1.75l-.185.092A1.082 1.082 0 0 1 10.5 7a1.082 1.082 0 0 1 1.565-.967M3 16v5.5h18V16");
}

.qi4hhgzkb {
  d: path("M7.625 2.5h8.75A2.625 2.625 0 0 1 19 5.125v3.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 8.875v-3.75A2.625 2.625 0 0 1 7.625 2.5");
}

</style>
