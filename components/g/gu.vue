<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="c9ml8vjxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gu" /></template>
<style>
.c9ml8vjxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.986 17.574v8.595a4.257 4.257 0 1 0 8.514 0v-8.595m-12.485 4.257a4.257 4.257 0 0 0-4.258-4.257h0a4.257 4.257 0 0 0-4.257 4.257v4.338a4.257 4.257 0 0 0 4.257 4.257h0a4.257 4.257 0 0 0 4.257-4.257h-4.257");
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
