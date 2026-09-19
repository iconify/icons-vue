<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="lrjg4jbym"/><path class="cd8_oc-7j"/><path class="upwoa7k1o"/><path class="tcgzz2v8t"/><path class="uongrccfh"/><path class="q4zsigb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:forgetmenot" /></template>
<style>
.cd8_oc-7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.28 11.61a10.77 10.77 0 1 0-7.64 19.57");
}

.lrjg4jbym {
  cx: 26.98px;
  cy: 26.29px;
  r: 6.37px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q4zsigb4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.73 24.68a11.75 11.75 0 1 0-21-8.86");
}

.tcgzz2v8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.53 20.45a8.73 8.73 0 1 0-4.06 12");
}

.uongrccfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.61 33.18A6.92 6.92 0 1 0 33.1 28m.12-.44a6.1 6.1 0 1 0-6.39-10.17");
}

.upwoa7k1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.31 29a9.2 9.2 0 0 0-.8 3.78a9.34 9.34 0 0 0 16.7 5.75m0-.05A8.72 8.72 0 1 0 37 22.62");
}

</style>
