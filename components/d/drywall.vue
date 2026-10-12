<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x9fyrobqy"/><path class="f937-hp8j"/><rect class="qy_piw5xf"/><path class="ldpitacyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drywall" /></template>
<style>
.f937-hp8j {
  d: path("M2.75 12h9.5m3.85 3h3.55q.6 0 .71.59l.78 4.32q.11.59-.49.59H15.1q-.6 0-.49-.59l.78-4.32q.11-.59.71-.59");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldpitacyg {
  d: path("M17.75 12.5V15");
}

.qy_piw5xf {
  width: 2.5px;
  height: 8.5px;
  x: 16.5px;
  y: 4px;
  rx: 1.25px;
}

.x9fyrobqy {
  width: 9.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
