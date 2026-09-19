<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="tdlvrpbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:letter-uppercase-square-s" /></template>
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

.tdlvrpbgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.017 30.247C19.998 31.524 21.228 32 22.94 32h2.369a3.99 3.99 0 0 0 3.991-3.991v-.018A3.99 3.99 0 0 0 25.31 24h-2.613a3.996 3.996 0 0 1-3.996-3.996h0A4.004 4.004 0 0 1 22.704 16h2.356c1.712 0 2.942.476 3.923 1.753");
}

</style>
