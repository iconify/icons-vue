<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="vmhoxibmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cibil" /></template>
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

.vmhoxibmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.325 20v8h4m-7.013-8v8m-1.05-8h2.101m-2.101 8h2.101m-12.376-8v8m-1.05-8h2.101m-2.101 8h2.101m-4.063-2.683v.033a2.65 2.65 0 1 1-5.3 0v-2.7a2.65 2.65 0 1 1 5.3 0v.033M25.3 24a2 2 0 1 1 0 4H22v-8h3.3a2 2 0 1 1 0 4m0 0h-3.296");
}

</style>
