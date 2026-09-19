<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="yg3xyh1ss"/><path class="z3jp-abef"/><ellipse class="otnzg9cmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:carvana" /></template>
<style>
.otnzg9cmw {
  cx: 23.889px;
  cy: 7.828px;
  rx: 10.533px;
  ry: 2.328px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yg3xyh1ss {
  d: path("M38.6 22.286c9.81-2.763-2.226-2.698-2.226-2.698l-3.56-4.817l-18.257.004l-3.012 4.683s-11.154.5-1.963 3.228l-3.99 4.832l-.04 14.601l4.652.163l.098-1.566l26.575.06l.07 1.724l5.461-.066V27.548z");
}

.z3jp-abef {
  d: path("M11.562 32.144c-.493 0-3.415-.012-5.262-.851c0 0-1.727-1.08.065-3.815c0 0 4.124-1.051 5.197 4.666m24.878-.106s1.824.526 5.592-1.136c0 0 .898-.745.058-2.565c0 0-3.21-2.443-5.65 3.701m-3.001-.486c-11.28-2.465-19.49-.097-19.49-.097s8.556 2.86 19.49.097M13.094 22.73l3.052-5.408l15.15-.033l3.823 5.476z");
}

</style>
