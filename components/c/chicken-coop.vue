<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tclzvrbzk"/><path class="f2_qgubmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chicken-coop" /></template>
<style>
.f2_qgubmt {
  d: path("M7.75 17.5v-2.25a1.75 1.75 0 0 1 3.5 0v2.25Zm-1.25 0v3.75m11-3.75v3.75m-6.25-3.75L15 21.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tclzvrbzk {
  d: path("M4.75 16.7v-5.65q0-.8.61-1.32l6.03-5.21q.61-.52 1.22 0l6.03 5.21q.61.52.61 1.32v5.65q0 .8-.8.8H5.55q-.8 0-.8-.8");
}

</style>
