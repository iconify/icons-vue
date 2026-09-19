<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="dga87kbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jins" /></template>
<style>
.dga87kbqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.829 19.365v9.27m-2.694-9.27v6.953a2.32 2.32 0 0 1-2.317 2.317h0a2.32 2.32 0 0 1-2.318-2.318v-.77m10.023 3.088v-9.27l6.142 9.27v-9.27m8.719 1.645a2.32 2.32 0 0 0-2.213-1.645h-1.495a2.324 2.324 0 0 0-2.317 2.317A2.31 2.31 0 0 0 32.676 24h1.506c1.287 0 2.318 1.031 2.318 2.317s-1.031 2.318-2.318 2.318h-1.494a2.32 2.32 0 0 1-2.214-1.646");
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

</style>
