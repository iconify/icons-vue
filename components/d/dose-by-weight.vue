<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z1438p8yn"/><path class="je5hb978g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dose-by-weight" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.je5hb978g {
  d: path("M9.25 16.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m2.75 0l1.75-1.75");
}

.z1438p8yn {
  d: path("M3 8.5h18m-11 0v-3l1-1v-2h2v2l1 1v3m-5.125 2.75h6.25a4.375 4.375 0 0 1 4.375 4.375v1.5a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125v-1.5a4.375 4.375 0 0 1 4.375-4.375");
}

</style>
