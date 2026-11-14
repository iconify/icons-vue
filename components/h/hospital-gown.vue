<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="opoqk5bzj"/><path class="w1fp426cy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-gown" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.opoqk5bzj {
  d: path("m9.482 3.061l1.65.943a1.75 1.75 0 0 0 1.736 0l1.65-.943a1.75 1.75 0 0 1 1.897.105l3.266 2.375a1.75 1.75 0 0 1 .454 2.342l-1.157 1.853A.875.875 0 0 1 17.75 10a.459.459 0 0 0-.712.401l.386 9.276a1.75 1.75 0 0 1-1.748 1.823H8.324a1.75 1.75 0 0 1-1.748-1.823l.386-9.276A.459.459 0 0 0 6.25 10a.875.875 0 0 1-1.228-.264L3.865 7.883a1.75 1.75 0 0 1 .454-2.342l3.266-2.375a1.75 1.75 0 0 1 1.897-.105");
}

.w1fp426cy {
  fill: currentColor;
  d: path("M8.75 11a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M13 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-4 3.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
