<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="akmah8e_a"/><rect class="q0_gb6qzx"/><path class="vcp1sqb1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:departure" /></template>
<style>
.akmah8e_a {
  d: path("M7.5 5.25v-2.5m9 2.5v-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q0_gb6qzx {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2px;
}

.vcp1sqb1g {
  d: path("M6 9.5h5.5m-5.5 5h5.5m3.25.5l3.5-3.5M15 11.25h3.25v3.25");
}

</style>
