<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="o307ktb6t"/><circle class="q687oe69d"/><path class="x2a8irtlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ai-score" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o307ktb6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 13.894l-10.336 7.509l3.948 12.151h12.776l3.948-12.151zm6.76 18.516a16.95 16.95 0 0 0 7.92 7.28m-9.03-21.7c1.6-4.33 4.88-7.83 9.03-9.68M45.5 24H33.492M7.13 10.69l1.1 7.97l-5.72 5.84m5.63 14h6.44l2.74 5.93m.292-10.876l-3.032 4.949m-.916-17.1l-5.435-2.747M24 45.5V33.55M24 2.5v11.39m0-6l-6.55-4.37");
}

.q687oe69d {
  cx: 27.076px;
  cy: 21.624px;
  r: 0.75px;
  fill: currentColor;
}

.x2a8irtlm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.076 23.377v3.946M24.29 25.35h-2.63m-.658 1.973l1.973-5.845l1.973 5.845");
}

</style>
