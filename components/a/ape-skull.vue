<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jgiaaebje"/><path class="pujnq4_bn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ape-skull" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jgiaaebje {
  d: path("M3.5 9.5C6 5 9.5 3 14 3s7 3.5 7 7.5q0 4.5-4.5 6l-1.5 4H8.5L3 17l2.5-4.5Z");
}

.pujnq4_bn {
  d: path("M8 10.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
