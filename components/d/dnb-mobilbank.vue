<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="rfjyt-bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dnb-mobilbank" /></template>
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

.rfjyt-bjw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.884 34.759V19.241l6.232 9.518V13.24M11.305 28.759v-9.518h2.117c2.273 0 4.115 1.864 4.115 4.164v1.19c0 2.3-1.842 4.164-4.115 4.164zM34.342 24c1.299 0 2.352 1.065 2.352 2.38s-1.053 2.379-2.352 2.379h-3.88v-9.518h3.88c1.299 0 2.352 1.065 2.352 2.38S35.64 24 34.342 24m.5 0h-3.88");
}

</style>
