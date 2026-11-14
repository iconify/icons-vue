<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5_oj5bzd"/><path class="q-l6c2b6s"/><path class="sj24qbb8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:isochrone-map" /></template>
<style>
.e5_oj5bzd {
  d: path("m4.077 5.551l4.25-1.771a1.75 1.75 0 0 1 1.346 0l4.654 1.94a1.75 1.75 0 0 0 1.346 0l2.904-1.21A1.75 1.75 0 0 1 21 6.125v10.708a1.75 1.75 0 0 1-1.077 1.616l-4.25 1.771a1.75 1.75 0 0 1-1.346 0l-4.654-1.94a1.75 1.75 0 0 0-1.346 0l-2.904 1.21A1.75 1.75 0 0 1 3 17.875V7.167a1.75 1.75 0 0 1 1.077-1.616");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q-l6c2b6s {
  d: path("M7 12c0-3 2.5-4.5 5.5-4.5c3 .25 4.5 2 4.25 4.5c-.25 3-2.25 4.75-5.25 4.5S7 14.5 7 12");
}

.sj24qbb8h {
  fill: currentColor;
  d: path("M10.75 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
