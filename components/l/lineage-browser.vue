<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="xshp7txei"/><path class="hgc9ibbzm"/><path class="px5x_3bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lineage-browser" /></template>
<style>
.hgc9ibbzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.086 9.24l1.603 4.064a14.2 14.2 0 0 0 8.007 8.007l4.065 1.603a1.168 1.168 0 0 1 0 2.172l-4.065 1.603a14.2 14.2 0 0 0-8.007 8.007l-1.603 4.065a1.168 1.168 0 0 1-2.172 0l-1.603-4.065a14.2 14.2 0 0 0-8.007-8.007l-4.065-1.603a1.168 1.168 0 0 1 0-2.172l4.065-1.603a14.2 14.2 0 0 0 8.007-8.007l1.603-4.065a1.168 1.168 0 0 1 2.172 0");
}

.px5x_3bwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.013 18.732a10.7 10.7 0 0 0 4.255 4.255h0a1.155 1.155 0 0 1 0 2.026h0a10.7 10.7 0 0 0-4.255 4.255h0a1.155 1.155 0 0 1-2.026 0h0a10.7 10.7 0 0 0-4.255-4.255h0a1.155 1.155 0 0 1 0-2.026h0a10.7 10.7 0 0 0 4.255-4.255h0a1.155 1.155 0 0 1 2.026 0");
}

.xshp7txei {
  cx: 24px;
  cy: 24px;
  r: 22.584px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
