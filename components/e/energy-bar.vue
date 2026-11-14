<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dbqv-ngch"/><path class="gt-ie4b2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-bar" /></template>
<style>
.dbqv-ngch {
  d: path("M10 5.5h10l1.5 3.25L20 12l1.5 3.25L20 18.5H10ZM10 9H4a1.5 1.5 0 0 0-1.5 1.5v3A1.5 1.5 0 0 0 4 15h6");
}

.gt-ie4b2u {
  d: path("M16.25 8.25L13.5 12.5h3l-2.75 3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
