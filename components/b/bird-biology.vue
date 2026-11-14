<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i1-q6xbid"/><path class="ngobb5bsi"/><path class="j3r4kdqko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bird-biology" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1-q6xbid {
  d: path("M14.075 16.481q-.283.02-.575.019C9 16.5 6.5 14 6 10L3 8l2.5-1c.5-2.5 2.5-4 5-4s4 2 4 4.5V9c2.5 1.5 5 1.75 7 1.5q-.352.705-.727 1.328M10 16v4.5m-.5-14h.01");
}

.j3r4kdqko {
  d: path("M21.5 14.5c0 3.75-5 3.75-5 7.5m.25-6.25h4.5m-4.5 5h4.5");
}

.ngobb5bsi {
  d: path("M16.5 14.5c0 3.75 5 3.75 5 7.5");
}

</style>
