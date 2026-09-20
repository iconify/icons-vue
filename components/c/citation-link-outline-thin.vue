<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e9_74sbem"/><path class="qymchdb9c"/><path class="sjow2h3vm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:citation-link-outline-thin" /></template>
<style>
.e9_74sbem {
  d: path("M2 14a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qymchdb9c {
  d: path("M13 6a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2Z");
}

.sjow2h3vm {
  d: path("m11 14 2 -2");
}

</style>
