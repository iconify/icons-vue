<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gizk7zb8c"/><rect class="u_hqpzbnr"/><rect class="vai_3cb-o"/><path class="zazonob0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bed-hotel" /></template>
<style>
.gizk7zb8c {
  d: path("M4.5 12V5.75A2.5 2.5 0 0 1 7 3.25h10a2.5 2.5 0 0 1 2.5 2.5V12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u_hqpzbnr {
  width: 9px;
  height: 2.5px;
  x: 7.5px;
  y: 6.5px;
  rx: 1.25px;
}

.vai_3cb-o {
  width: 18.5px;
  height: 5.5px;
  x: 2.75px;
  y: 12px;
  rx: 1.5px;
}

.zazonob0v {
  d: path("M4.5 17.5v3.75m15-3.75v3.75");
}

</style>
