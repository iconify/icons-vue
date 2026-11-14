<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ha0gnrbxt"/><path class="f3s2rzb6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-cost" /></template>
<style>
.f3s2rzb6d {
  d: path("M10.75 7.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-1.75 6c0-2 1.5-2.5 3-1.75c1.5-.75 3-.25 3 1.75c0 1.75-.75 2.75-1 4l-.5 1.75L12 17l-1.5 2.5l-.5-1.75c-.25-1.25-1-2.25-1-4");
}

.ha0gnrbxt {
  d: path("m13.78 4.144l3.875 3.576a2.63 2.63 0 0 1 .845 1.929v9.226a2.625 2.625 0 0 1-2.625 2.625h-7.75A2.625 2.625 0 0 1 5.5 18.875V9.649a2.63 2.63 0 0 1 .845-1.929l3.875-3.576a2.625 2.625 0 0 1 3.56 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
