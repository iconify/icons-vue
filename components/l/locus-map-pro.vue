<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rre7ohb4h"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:locus-map-pro" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.rre7ohb4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24h7.899v1.297a4 4 0 1 0 3 0V24H24m0 18.5v-7.899h1.297a4 4 0 1 0 0-3H24V24m18.5 0h-7.899v-1.297a4 4 0 1 0-3 0V24H24m0-18.5v7.899h-1.297a4 4 0 1 0 0 3H24V24");
}

</style>
