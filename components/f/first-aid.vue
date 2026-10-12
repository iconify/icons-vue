<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="p5qv0z-1c"/><path class="omv028h1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:first-aid" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.omv028h1c {
  d: path("M8.75 6.75V5a2 2 0 0 1 2-2h2.5a2 2 0 0 1 2 2v1.75m-3.25 4v6.5M8.75 14h6.5");
}

.p5qv0z-1c {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 2.5px;
}

</style>
