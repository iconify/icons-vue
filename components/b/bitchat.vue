<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="z2o791b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitchat" /></template>
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

.z2o791b5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.547 28.9h2.906m-2.906-9.8h2.906M24 19.1v9.8m5.084-9.8H35.5m-3.208 9.8v-9.8M16.495 24c1.337 0 2.421 1.097 2.421 2.45s-1.084 2.45-2.421 2.45H12.5v-9.8h3.995c1.337 0 2.421 1.097 2.421 2.45S17.832 24 16.495 24m0 0h-3.99");
}

</style>
