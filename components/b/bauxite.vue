<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pxhaeo60s"/><path class="zapppkbwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bauxite" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pxhaeo60s {
  d: path("m2.954 17.383l.983-4.589a1.8 1.8 0 0 1 .221-.55l3.493-5.676a1.75 1.75 0 0 1 .987-.759l3.697-1.11a1.75 1.75 0 0 1 1.286.111l3.888 1.945a1.75 1.75 0 0 1 .754.727l2.555 4.684a1.75 1.75 0 0 1 .209.713l.339 4.746a1.75 1.75 0 0 1-1.745 1.875H4.665a1.75 1.75 0 0 1-1.711-2.117");
}

.zapppkbwb {
  d: path("m8 6l2 5.5l5 1");
}

</style>
