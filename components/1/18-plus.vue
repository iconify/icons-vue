<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="o8cud-pla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:18-plus" /></template>
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

.o8cud-pla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.5 20.179l2.625-1.429v10.5M22.228 24a2.625 2.625 0 0 0-2.625 2.625v0a2.625 2.625 0 0 0 2.625 2.625h1.706a2.625 2.625 0 0 0 2.625-2.625v0A2.625 2.625 0 0 0 23.934 24m0 0a2.625 2.625 0 0 0 2.625-2.625v0a2.625 2.625 0 0 0-2.625-2.625h-1.706a2.625 2.625 0 0 0-2.625 2.625v0A2.625 2.625 0 0 0 22.228 24m0 0h1.706m5.316 0h5.25m-2.625-2.625v5.25");
}

</style>
