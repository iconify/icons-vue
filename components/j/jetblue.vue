<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="b2gy6_-ue"/><circle class="cyz18so9w"/><path class="uco87_-6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jetblue" /></template>
<style>
.b2gy6_-ue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.981 21.956v5.8c0 .66-.529 1.193-1.182 1.193h0c-.326 0-.621-.133-.835-.349");
}

.cyz18so9w {
  cx: 10.981px;
  cy: 19.801px;
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

.uco87_-6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.191 25.73a1.76 1.76 0 0 1-1.528.888h0a1.76 1.76 0 0 1-1.76-1.76v-1.143c0-.971.788-1.76 1.76-1.76h0c.971 0 1.76.789 1.76 1.76v.572h-3.52m25.903 1.443c-.303.53-.875.888-1.53.888h0a1.76 1.76 0 0 1-1.759-1.76v-1.143c0-.971.788-1.76 1.76-1.76h0c.972 0 1.76.789 1.76 1.76v.572h-3.52m-16.946-3.783v5.235c0 .485.394.88.88.88h.264m-2.067-4.663h1.847m4.73 1.144a1.76 1.76 0 0 1 0 3.518h-2.903v-7.037h2.903a1.76 1.76 0 0 1 0 3.518m0 0h-2.903m6.301-3.519v6.159c0 .485.394.88.88.88h.263m1.389-4.663v2.903c0 .972.787 1.76 1.759 1.76h0a1.76 1.76 0 0 0 1.76-1.76v-2.903m-.001 2.903v1.759");
}

</style>
