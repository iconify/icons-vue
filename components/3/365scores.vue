<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="fy5b7mnje"/><path class="u8aaz4-8c"/><path class="bsiv8ibmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:365scores" /></template>
<style>
.bsiv8ibmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.923 19.835c.692-.576 1.438-.84 3.112-.835l.388.002a2.5 2.5 0 1 1 0 4.999m-1.921 0h1.921m14.529 4.156c.69.578 1.36.843 3.034.843h.288a2.804 2.804 0 0 0 0-5.607h-3.322V19h6.125");
}

.fy5b7mnje {
  cx: 23.953px;
  cy: 25.688px;
  r: 3.313px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.u8aaz4-8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.972 20.22C26.42 19.497 25.58 19 24.185 19h-.232a3.313 3.313 0 0 0-3.313 3.313v3.375m-8.716 2.469c.69.578 1.436.843 3.11.843h.39a2.5 2.5 0 1 0 0-4.999");
}

</style>
