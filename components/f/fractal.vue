<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o-p0o_7ce"/><path class="x9pjyfcdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fractal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o-p0o_7ce {
  d: path("m13.3 6.008l6.905 11.994a1.5 1.5 0 0 1-1.299 2.248H5.094a1.5 1.5 0 0 1-1.299-2.248L10.7 6.008a1.5 1.5 0 0 1 2.6 0");
}

.x9pjyfcdo {
  d: path("M9.844 12h4.312a1.5 1.5 0 0 1 1.299 2.248L13.3 17.992a1.5 1.5 0 0 1-2.6 0l-2.155-3.744A1.5 1.5 0 0 1 9.844 12");
}

</style>
