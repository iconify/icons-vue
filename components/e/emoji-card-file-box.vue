<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jor8otb9y"/><path class="xgjqwebez"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-card-file-box" /></template>
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

.jor8otb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.118 17.359a1.4 1.4 0 0 0-.82-.263h-6.146a1.41 1.41 0 0 0-1.41 1.41v.656m18.289 1.076a1.41 1.41 0 0 0-1.267-.791h-6.146a1.41 1.41 0 0 0-1.41 1.41v.981H9.743m28.33 2.964v-.888c0-.705-.63-1.276-1.41-1.276h-6.146c-.778 0-1.409.571-1.409 1.276v.888H9.743");
}

.xgjqwebez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.52 11.886l.008 15.948H42.5l-.01-15.948m0-.001H5.5m.028 15.949H42.5m-23.992 3.659h11.115v5.278H18.508z");
}

</style>
