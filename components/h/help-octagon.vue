<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="azc-qcbut"/><path class="cpfshnrsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:help-octagon" /></template>
<style>
.azc-qcbut {
  d: path("M9.087 2.5h5.826a2.63 2.63 0 0 1 1.856.769l3.962 3.962a2.63 2.63 0 0 1 .769 1.856v5.826a2.63 2.63 0 0 1-.769 1.856l-3.962 3.962a2.63 2.63 0 0 1-1.856.769H9.087a2.63 2.63 0 0 1-1.856-.769l-3.962-3.962a2.63 2.63 0 0 1-.769-1.856V9.087a2.63 2.63 0 0 1 .769-1.856l3.962-3.962A2.63 2.63 0 0 1 9.087 2.5");
}

.cpfshnrsz {
  d: path("M9.5 9.5a2.5 2.5 0 1 1 3.75 2.25c-.75.5-1.25 1-1.25 2V14m0 3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
