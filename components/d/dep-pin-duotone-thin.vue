<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iwwntwb1x"/><path class="c0mv5nb8z"/><path class="h18rabcld"/><path class="fwgh9qb5h"/><path class="nwn4xu84s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dep-pin-duotone-thin" /></template>
<style>
.c0mv5nb8z {
  fill: currentColor;
  d: path("M14.5 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fwgh9qb5h {
  d: path("M14.5 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.h18rabcld {
  d: path("M3 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iwwntwb1x {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nwn4xu84s {
  d: path("M17.5 14v4.5");
}

</style>
