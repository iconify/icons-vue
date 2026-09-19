<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-64.44 20.63 23.233)" class="x0b53bsdm"/><path class="o3cp0zxsy"/><ellipse transform="rotate(-64.44 20.63 23.233)" class="pmkizdbha"/><path class="wt90lgb0j"/><path class="upodscbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:juicessh" /></template>
<style>
.o3cp0zxsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.47 25.67l-6.81 14.24M28.6 6.57l-6.81 14.24m-3.22 3.15L5.74 28.5m29.79-10.52l-12.84 4.53m-3.76-.08L7.98 17.19m25.3 12.1l-10.95-5.24m-2.46-2.97l-4.5-12.74m10.52 29.79L21.36 25.3");
}

.pmkizdbha {
  cx: 20.63px;
  cy: 23.24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.7px;
  ry: 1.88px;
}

.upodscbtw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.6 6.57c11.14 5.33 16.6 17.11 12.2 26.31s-17 12.35-28.14 7");
}

.wt90lgb0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.47 25.67c-.51 1.07-3.93 2-4.52 3.22a1.24 1.24 0 0 0 .66 1.87a1.29 1.29 0 0 0 1.78-.76");
}

.x0b53bsdm {
  cx: 20.63px;
  cy: 23.24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 18.48px;
  ry: 14.02px;
}

</style>
