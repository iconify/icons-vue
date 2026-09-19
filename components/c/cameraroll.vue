<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lfq1rgbib"/><path class="j41zn6h1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cameraroll" /></template>
<style>
.j41zn6h1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.72 12.84H18.15a2 2 0 0 0-1.95 1.95l.05 21.32a2 2 0 0 0 1.95 1.94h12.52");
}

.lfq1rgbib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.17 5.5a2 2 0 0 0-1.95 2v.94h-3A2.6 2.6 0 0 0 5.5 10.9V40a2.6 2.6 0 0 0 2.68 2.5H28a2.6 2.6 0 0 0 2.72-2.5v-1.95h9.83a1.94 1.94 0 0 0 2-1.94V14.79a2 2 0 0 0-2-1.95h-9.83V10.9A2.6 2.6 0 0 0 28 8.39h-3.09v-.94A2 2 0 0 0 23 5.5Zm5.93 10.67h3v3h-3Zm5.82 0h3v3h-3Zm5.86 0h3v3h-3Zm5.83 0h3v3h-3ZM19.1 31.75h3v3h-3Zm5.82 0h3v3h-3Zm5.86 0h3v3h-3Zm5.83 0h3v3h-3Z");
}

</style>
