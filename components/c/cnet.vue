<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="h7c49zb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cnet" /></template>
<style>
.h7c49zb-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.693 18.022v8.272c0 .768.622 1.39 1.39 1.39h.417m-1.807-7.368h1.459m-23.457 5.968a2.78 2.78 0 0 1-2.415 1.4h0a2.78 2.78 0 0 1-2.78-2.78v-1.808a2.78 2.78 0 0 1 2.78-2.78h0a2.78 2.78 0 0 1 2.412 1.396m11.211 5.972v-4.588a2.78 2.78 0 0 0-2.78-2.78h0a2.78 2.78 0 0 0-2.78 2.78m-.001 4.588v-7.368m13.413 5.964a2.78 2.78 0 0 1-2.416 1.404h0a2.78 2.78 0 0 1-2.78-2.78v-1.808a2.78 2.78 0 0 1 2.78-2.78h0a2.78 2.78 0 0 1 2.78 2.78V24h-5.56M17.455 34.426V13.573");
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
