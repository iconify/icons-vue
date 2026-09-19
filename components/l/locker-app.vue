<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="v2510ac8h"/><path class="kjwf1sb5w"/><rect class="b107x_bsu"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:locker-app" /></template>
<style>
.b107x_bsu {
  width: 4.201px;
  height: 6.34px;
  x: 26.845px;
  y: 20.784px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.1px;
  ry: 2.1px;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kjwf1sb5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.295 20.784l-2.1 6.341l-2.101-6.341m22.903 5.646c.388.506.876.695 1.554.695h.939c.873 0 1.582-.708 1.582-1.582v-.007c0-.873-.709-1.581-1.582-1.581h-1.036a1.583 1.583 0 0 1-1.583-1.584h0c0-.876.71-1.587 1.587-1.587h.933c.679 0 1.166.189 1.555.695m-12.044 3.52v.026a2.1 2.1 0 0 1-2.1 2.1h0a2.1 2.1 0 0 1-2.1-2.1v-2.14c0-1.16.94-2.1 2.1-2.1h0c1.16 0 2.1.94 2.1 2.1v.026m-8.63 1.044h2.067m1.103 3.17h-3.17v-6.341h3.17");
}

.v2510ac8h {
  cx: 39.509px;
  cy: 19.199px;
  r: 1.585px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
