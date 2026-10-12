<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e_k254mvu"/><circle class="gp0egaclj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brooch" /></template>
<style>
.e_k254mvu {
  d: path("m12.82 3.82l.68.47q.82.58 1.82.6l.82.01q1 .02 1.33.97l.27.78q.33.94 1.13 1.54l.65.5q.8.61.51 1.56l-.24.79q-.29.96 0 1.92l.24.79q.29.95-.51 1.56l-.65.5q-.8.6-1.13 1.54l-.27.78q-.33.95-1.33.97l-.82.01q-1 .02-1.82.6l-.68.47q-.82.57-1.64 0l-.68-.47q-.82-.58-1.82-.6l-.82-.01q-1-.02-1.33-.97l-.27-.78q-.33-.94-1.13-1.54l-.65-.5q-.8-.61-.51-1.56l.24-.79q.29-.96 0-1.92l-.24-.79q-.29-.95.51-1.56l.65-.5q.8-.6 1.13-1.54l.27-.78q.33-.95 1.33-.97l.82-.01q1-.02 1.82-.6l.68-.47q.82-.57 1.64 0");
}

.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
