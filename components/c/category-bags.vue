<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h4sgjxbsw"/><path class="a0km0crlg"/><path class="k0qhlgbxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-bags" /></template>
<style>
.a0km0crlg {
  d: path("m4.25 12.5l7.75 4l7.75-4");
}

.h4sgjxbsw {
  d: path("M2.5 21L5 9h14l2.5 12Zm6-12V7a3.5 3.5 0 0 1 7 0v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0qhlgbxp {
  fill: currentColor;
  d: path("M10.5 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
