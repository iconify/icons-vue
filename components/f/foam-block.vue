<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p58xsb53w"/><path class="d20w4197e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:foam-block" /></template>
<style>
.d20w4197e {
  d: path("M3 10q3-2.5 6.25 0t6.25 0v11m0-11l5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p58xsb53w {
  d: path("M3 21V10l5-5q3-2.5 6.25 0t6.25 0v11l-5 5Z");
}

</style>
