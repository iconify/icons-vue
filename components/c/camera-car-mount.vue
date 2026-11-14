<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lbdvc5t_e"/><path class="d_dz7_quh"/><path class="hkiztmb1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-car-mount" /></template>
<style>
.d_dz7_quh {
  d: path("M4.75 12.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m8 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m2.25 5.5a1 1 0 0 1 1-1h.75l.75-1H19l.75 1h.75a1 1 0 0 1 1 1v2.5a1 1 0 0 1-1 1H16a1 1 0 0 1-1-1Z");
}

.hkiztmb1x {
  d: path("M17 19.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lbdvc5t_e {
  d: path("M2.5 11V8.5A1.5 1.5 0 0 1 4 7h1l2.5-3.5H13L15.75 7H18a1.5 1.5 0 0 1 1.5 1.5V11Z");
}

</style>
