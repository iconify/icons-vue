<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o70lt9bat"/><path class="zuo752-mb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:graduate-program" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o70lt9bat {
  d: path("m12.671 5.335l5.646 2.823a1.5 1.5 0 0 1 0 2.684l-5.646 2.823a1.5 1.5 0 0 1-1.342 0l-5.646-2.823a1.5 1.5 0 0 1 0-2.684l5.646-2.823a1.5 1.5 0 0 1 1.342 0");
}

.zuo752-mb {
  d: path("M7 12v4.5c1.5 1.25 3.25 1.75 5 1.75s3.5-.5 5-1.75V12m3-2v5");
}

</style>
