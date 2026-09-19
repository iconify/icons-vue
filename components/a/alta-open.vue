<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="o1q87u50e"/><path class="q5obtzb_i"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alta-open" /></template>
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

.o1q87u50e {
  cx: 13.316px;
  cy: 23.925px;
  r: 2.816px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q5obtzb_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.652 26.456a2.816 2.816 0 1 0-1.58-2.531v4.966m12.594-3.218a2.816 2.816 0 1 1 .608-1.748h-5.632m7.571 2.816v-3.489a2.144 2.144 0 0 1 4.287 0v3.49");
}

</style>
