<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m520f8box"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:justdial" /></template>
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

.m520f8box {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.6 15.9v12.15a4.05 4.05 0 0 1-4.05 4.05h0a4.05 4.05 0 0 1-4.05-4.05v-1.345m21-1.287a4.05 4.05 0 0 0-4.05-4.05h0a4.05 4.05 0 0 0-4.05 4.05v2.632a4.05 4.05 0 0 0 4.05 4.05h0a4.05 4.05 0 0 0 4.05-4.05m0 4.051V15.899");
}

</style>
