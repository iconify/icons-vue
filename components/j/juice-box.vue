<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j8cpct04c"/><path class="jqtnobcpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:juice-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8cpct04c {
  d: path("M5.75 7.75h12.5l-1.4 12.1a1.5 1.5 0 0 1-1.5 1.4h-6.7a1.5 1.5 0 0 1-1.5-1.4Z");
}

.jqtnobcpa {
  d: path("m12.75 12.25l2-9.5h3M6.4 12.25h11.2");
}

</style>
