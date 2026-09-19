<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="px4bnm_ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ihg-hotel" /></template>
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

.px4bnm_ld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.479 18.216v11.568m5.001-11.568v11.568M24 18.216v11.568m-7.52-5.806H24m12.521-1.93c0-2.116-1.683-3.832-3.76-3.832s-3.76 1.716-3.76 3.832v3.904c0 2.116 1.683 3.832 3.76 3.832s3.76-1.716 3.76-3.832h-3.76");
}

</style>
