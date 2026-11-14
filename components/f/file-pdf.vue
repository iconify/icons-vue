<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tuq82lbhh"/><path class="a9ejvke2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:file-pdf" /></template>
<style>
.a9ejvke2o {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-16.25 13v-6h2a2 2 0 0 1 0 4h-2m6.75-4h1a3 3 0 0 1 0 6h-1Zm10.75 0h-4v6m0-3h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tuq82lbhh {
  d: path("M4.5 12V5A2.5 2.5 0 0 1 7 2.5h6.5l6 6V12");
}

</style>
