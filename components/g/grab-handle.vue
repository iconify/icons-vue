<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="roliryp-r"/><path class="oaevkhoua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grab-handle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oaevkhoua {
  d: path("M7 15.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.roliryp-r {
  d: path("M2.5 4h19M10.25 4v4.5l1.75 2l1.75-2V4");
}

</style>
