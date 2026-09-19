<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g7mz4bc9x"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:log28" /></template>
<style>
.g7mz4bc9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29 35.5H11m26 6.954v-4.74h-2.234c-1.117 0-2.016-.9-2.016-2.016v-.538c0-1.117.9-2.016 2.016-2.016H37v-6.68h-2.484c-1.117 0-2.016-.9-2.016-2.016v-.538c0-1.117.9-2.016 2.016-2.016H37v-6.93h-2.484c-1.117 0-2.016-.9-2.016-2.016v-.538c0-1.116.9-2.015 2.016-2.015H37V5.54M29 24.5H11m13-11H11");
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
