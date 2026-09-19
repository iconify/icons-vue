<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><path class="ramkzm7cd"/><rect class="oeeumh0go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:edge-screen-note10" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oeeumh0go {
  width: 8.005px;
  height: 12.082px;
  x: 9.5px;
  y: 17.959px;
  rx: 4.002px;
  ry: 4.002px;
}

.ramkzm7cd {
  d: path("M20.98 30.041v-8.08a4 4 0 0 1 4.002-4.002h0a4 4 0 0 1 4.002 4.002v8.08M32.459 24h3.939m2.102 6.041h-2.039a4 4 0 0 1-4.002-4.002V21.96a4 4 0 0 1 4.002-4.002H38.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
