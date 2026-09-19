<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="jpe04fb-q"/><circle class="abv6p9kaf"/><path class="tsd9kibzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linkt" /></template>
<style>
.abv6p9kaf {
  cx: 19.023px;
  cy: 20.248px;
  r: 0.75px;
  fill: currentColor;
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

.jpe04fb-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.755 19.982v8.52h4.26m10.422-8.52v8.52m.001-1.81l3.856-3.838m-2.629 2.617l3.032 3.018");
}

.tsd9kibzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.023 22.857v5.645M34.127 21.1v7.402m-2.833-5.645h3.951m-9.91 5.645v-3.515a2.13 2.13 0 0 0-2.13-2.13h0a2.13 2.13 0 0 0-2.13 2.13m0 3.515v-5.645");
}

</style>
