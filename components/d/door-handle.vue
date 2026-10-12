<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nfu3paclw"/><rect class="xtm28ccvs"/><path class="nm0yidbtw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:door-handle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nfu3paclw {
  width: 7px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 3.5px;
}

.nm0yidbtw {
  d: path("M7.25 14.5v3");
}

.xtm28ccvs {
  width: 10.5px;
  height: 4px;
  x: 10.75px;
  y: 6.5px;
  rx: 2px;
}

</style>
