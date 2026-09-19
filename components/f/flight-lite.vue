<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sgja_16tr"/><path class="l36y90b6g"/><path class="s2x7-2t9t"/><path class="zii-_7bix"/><path class="tikan1bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flight-lite" /></template>
<style>
.l36y90b6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.453 42.5C-2.01 30.302 30.705 14.158 23.57 3.5C43.156 18.543.576 29.485 8.453 42.5");
}

.s2x7-2t9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.324 32.944c-5.205 4.31-16.323.532-20.87 9.556h0c2.281-4.327 13.057-3.291 19.215-5.429m4.261-6.003a10 10 0 0 0-.38-1.55c-.33 1.052-.8 1.9-1.383 2.59");
}

.sgja_16tr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.453 42.5C6.957 29.136 33.028 27.024 31.885 16.09C42.325 33.7 8.625 30.243 8.453 42.5");
}

.tikan1bqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.63 33.5v8h4");
}

.zii-_7bix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.63 37.5a7 7 0 1 1-14 0a7 7 0 0 1 14 0");
}

</style>
