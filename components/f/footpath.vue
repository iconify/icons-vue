<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pyqln2b_q"/><circle class="zanv7q--q"/><path class="it605fbmt"/><circle class="f-7dtmabf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:footpath" /></template>
<style>
.f-7dtmabf {
  cx: 17px;
  cy: 14.75px;
  r: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it605fbmt {
  d: path("M14.25 6.5a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0");
}

.pyqln2b_q {
  d: path("M4.25 11.5a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0");
}

.zanv7q--q {
  cx: 7px;
  cy: 19.75px;
  r: 1.5px;
}

</style>
