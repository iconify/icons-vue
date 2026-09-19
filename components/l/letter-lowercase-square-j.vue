<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="cdb83q58c"/><circle class="w-6ipp0zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:letter-lowercase-square-j" /></template>
<style>
.cdb83q58c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.007 18.275v12c0 2.21-1.774 4-3.962 4h0a3.93 3.93 0 0 1-2.802-1.172");
}

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

.w-6ipp0zu {
  cx: 27.007px;
  cy: 14.475px;
  r: 0.75px;
  fill: currentColor;
}

</style>
