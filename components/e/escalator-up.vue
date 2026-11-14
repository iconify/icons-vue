<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i63wbqccw"/><path class="oo8vqmwgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:escalator-up" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i63wbqccw {
  d: path("M2.5 20h4v-3h3v-3h3v-3h3V8h6v3l-9 9Z");
}

.oo8vqmwgc {
  d: path("M2.5 14.5H5L14.5 5h7");
}

</style>
