<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tt2-byrmn"/><circle class="dxpm0udmg"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:devcheck" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dxpm0udmg {
  cx: 24.799px;
  cy: 13.973px;
  r: 2.86px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tt2-byrmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.885 22.726c2.313-1.313 5.31-2.691 7-2.691c1.64 0-4.255 16.852-3.1 16.852a11.75 11.75 0 0 0 6.874-2.673");
}

</style>
