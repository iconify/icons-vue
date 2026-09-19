<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d7da7lb2x"/><path class="t345l3bmu"/><circle class="b6rvelb_x"/><path class="ggclsi53t"/><path class="mztkifbam"/><circle class="oe6v2-_-l"/><path class="mz_24bcrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aha-games" /></template>
<style>
.b6rvelb_x {
  cx: 12.814px;
  cy: 22.385px;
  r: 2.443px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d7da7lb2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 17.256h-1.526v-2.624l-4.089-1.587l-4.333-1.038h-2.289L5.69 17.805L4.5 27.876l3.174 8.117l14.8-18.737m-4.089-4.211v14.77");
}

.ggclsi53t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.257 22.385v-4.519h-3.998v2.635M24 17.256h1.526v-2.624l4.089-1.587l4.333-1.038h2.289l6.073 5.798l1.19 10.071l-3.174 8.117l-5.14-6.507m-5.571-16.441v14.77");
}

.mz_24bcrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.582 18.05v4.519h3.998v-2.635m-2.394 9.552l7.153-11.436");
}

.mztkifbam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.186 29.486l-9.691-2.19V25.16H24");
}

.oe6v2-_-l {
  cx: 36.025px;
  cy: 18.05px;
  r: 2.443px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t345l3bmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.814 29.486l9.691-2.19V25.16H24");
}

</style>
