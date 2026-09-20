<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="fptplk14x"/><path class="fkkf-acvy"/></g><g class="y9tr6bcfx"><rect class="w5ztvbg7m"/><path class="w9v12qzbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-simple-3" /></template>
<style>
.fkkf-acvy {
  d: path("M19.2 21.336c1.107-.922 2.3-1.343 4.979-1.336l.622.004a4 4 0 1 1 0 7.998m-3.074 0h3.074");
}

.fptplk14x {
  d: path("M19.202 34.65c1.104.926 2.297 1.35 4.975 1.35h.624a4 4 0 1 0 0-7.998");
}

.w5ztvbg7m {
  width: 35px;
  height: 36px;
  x: 6.5px;
  y: 7.5px;
  rx: 4px;
  ry: 4px;
}

.w9v12qzbx {
  d: path("M33.5 4.5v6m-19-6v6");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
