<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="esi2rximu"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cove" /></template>
<style>
.esi2rximu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.853 21.318l-2.024 5.364l-2.024-5.364m-7.523 4.344a2.02 2.02 0 0 1-1.758 1.02h0a2.024 2.024 0 0 1-2.024-2.024v-1.316c0-1.118.906-2.024 2.024-2.024h0c.75 0 1.406.409 1.756 1.016m16.955 3.326a2.02 2.02 0 0 1-1.759 1.022h0a2.024 2.024 0 0 1-2.024-2.024v-1.316c0-1.118.906-2.024 2.024-2.024h0c1.118 0 2.024.906 2.024 2.024V24h-4.048m-11.209-.658a2.024 2.024 0 0 1 4.048 0v1.316a2.024 2.024 0 0 1-4.048 0z");
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
