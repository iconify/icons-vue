<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vilsfcbox"/><path class="y_evnvbxu"/><path class="ixv163bsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:attic" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixv163bsh {
  d: path("M10 21v-4h4v4");
}

.vilsfcbox {
  fill: currentColor;
  d: path("m3.5 10.5l8.5-7l8.5 7Z");
}

.y_evnvbxu {
  d: path("M3.5 10.5V21h17V10.5");
}

</style>
