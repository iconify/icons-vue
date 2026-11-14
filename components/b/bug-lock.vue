<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rc1g9kzzv"/><path class="c-64mxcqb"/><path class="oeuqu_z4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bug-lock" /></template>
<style>
.c-64mxcqb {
  d: path("M7.25 8.5a2.5 2.5 0 0 1 4.5 0M2.5 11l3 1m11-1l-3 1m-11 3l3-.5m11 .5l-3-.5M3 19l2.75-1.75m11-.25h2.5A1.75 1.75 0 0 1 21 18.75v1a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-1A1.75 1.75 0 0 1 16.75 17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oeuqu_z4g {
  d: path("M16.25 17v-1.25a1.75 1.75 0 0 1 3.5 0V17");
}

.rc1g9kzzv {
  d: path("M5.5 13.25a4 5.25 0 1 0 8 0a4 5.25 0 1 0-8 0");
}

</style>
