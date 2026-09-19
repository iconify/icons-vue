<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xx45aikpx"/><path class="o3i63qbzo"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dji" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.o3i63qbzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.393 19.439l-3.375 12.595a2.31 2.31 0 0 1-2.229 1.71h-8.056m16.771-4.991L37 19.439");
}

.xx45aikpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.143 14.256l-3.52 13.138a1.83 1.83 0 0 1-1.771 1.358h-9.018a1.833 1.833 0 0 1-1.77-2.307l1.513-5.648a1.83 1.83 0 0 1 1.77-1.358h8.09");
}

</style>
