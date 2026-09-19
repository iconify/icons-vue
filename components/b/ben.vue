<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="y81il-bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ben" /></template>
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

.y81il-bfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.793 28.86a3.25 3.25 0 0 1-2.824 1.64h0a3.25 3.25 0 0 1-3.25-3.25v-2.112a3.25 3.25 0 0 1 3.25-3.25h0a3.25 3.25 0 0 1 3.25 3.25v1.056h-6.5M36.907 30.5v-5.362a3.25 3.25 0 0 0-3.25-3.25h0a3.25 3.25 0 0 0-3.25 3.25V30.5m0-5.363v-3.25M16.456 24a3.25 3.25 0 0 1 0 6.5h-5.363v-13h5.363a3.25 3.25 0 0 1 0 6.5m0 0h-5.363");
}

</style>
