<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q6o4qiqpc"/><path class="xe8fpwble"/><circle class="d4qzsfumr"/><path class="xl0efgbgk"/><path class="cmwgxnb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diatronome" /></template>
<style>
.cmwgxnb_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.001 31.69a4.205 4.205 0 1 1-4.204 4.205M26.311 7.95l11.73 11.73M9.96 24.302l11.729 11.73M30.77 9.437l11.73 11.73m-37 1.649l11.73 11.73");
}

.d4qzsfumr {
  cx: 26.892px;
  cy: 24.882px;
  r: 1.584px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q6o4qiqpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.316 7.9l11.779 11.78a7.358 7.358 0 1 1-10.406 10.405L9.91 18.305");
}

.xe8fpwble {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.316 7.9l-2.23 2.23l11.779 11.779a4.205 4.205 0 1 1-5.946 5.946l-11.78-11.779l-2.229 2.23");
}

.xl0efgbgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.012 23.763l-12.878-10.68m10.638 12.919l-10.64-12.92m17.961 15.762l5.296 5.296m-7.534-3.056l5.295 5.296m2.24-2.24a1.584 1.584 0 1 1-2.24 2.24");
}

</style>
