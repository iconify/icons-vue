<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ahlvx9bqz"/><circle class="jv0-78bwd"/><rect class="k3qm-mbda"/><path class="axb-myu8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fdroidforum" /></template>
<style>
.ahlvx9bqz {
  cx: 16.99px;
  cy: 15.18px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.axb-myu8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.83L9.16 9.5M42.5 5.85l-3.66 3.67m.043 32.459L22.99 37.374l-11.841-.167a2.794 2.794 0 0 1-2.8-2.8V27.47a2.794 2.794 0 0 1 2.8-2.8h25.72a2.794 2.794 0 0 1 2.8 2.8v7.105a2.794 2.794 0 0 1-2.8 2.8h-1.705Z");
}

.jv0-78bwd {
  cx: 31.01px;
  cy: 15.18px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k3qm-mbda {
  width: 31.32px;
  height: 12.99px;
  x: 8.35px;
  y: 8.68px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.8px;
}

</style>
