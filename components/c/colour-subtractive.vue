<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fpb5dob1t"/><path class="bt-n2_26o"/><path class="i5gy7caza"/><path class="fellzrbni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-subtractive" /></template>
<style>
.bt-n2_26o {
  d: path("M10 9a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.fellzrbni {
  fill: currentColor;
  d: path("M10 9.75a5.5 5.5 0 0 1 4 0a5.5 5.5 0 0 1-2 3.5a5.5 5.5 0 0 1-2-3.5");
}

.fpb5dob1t {
  d: path("M3 9a5.5 5.5 0 1 0 11 0A5.5 5.5 0 1 0 3 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5gy7caza {
  d: path("M6.5 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
