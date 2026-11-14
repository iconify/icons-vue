<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ma6cq1dcd"/><path class="g98v4dscn"/><path class="es_1s5bpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:citizenship" /></template>
<style>
.es_1s5bpx {
  d: path("M10.25 10.5a1.75 3.75 0 1 0 3.5 0a1.75 3.75 0 1 0-3.5 0m.005 7.047l4.951-.696");
}

.g98v4dscn {
  d: path("M8.041 10.515a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ma6cq1dcd {
  d: path("m7.846 4l5.942-.835a3.5 3.5 0 0 1 3.953 2.979l1.392 9.903A3.5 3.5 0 0 1 16.154 20l-5.942.835a3.5 3.5 0 0 1-3.953-2.979L4.867 7.953A3.5 3.5 0 0 1 7.846 4");
}

</style>
