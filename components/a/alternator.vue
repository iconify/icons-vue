<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-8s6cb1u"/><path class="bmm9uobmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alternator" /></template>
<style>
.bmm9uobmc {
  d: path("m9.75 10.5l-2.25 4h3l-2.25 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-8s6cb1u {
  d: path("M2.5 14a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0M16 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-1.25 11.75l6-10.5M6.5 8l11-4.75");
}

</style>
