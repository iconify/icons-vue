<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="tro6busfo"/><path class="u_n8_pwyh"/><path class="i-_5hpbhq"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:immowelt" /></template>
<style>
.i-_5hpbhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.877 19.23a2.18 2.18 0 0 1 2.173-2.173a2.18 2.18 0 0 1 2.174 2.173v3.26m4.226 0a2.056 2.056 0 0 1-2.05-2.05v-1.333c0-1.128.922-2.05 2.05-2.05s2.05.923 2.05 2.05v1.333c0 1.128-.923 2.05-2.05 2.05m-15.601 5.905l-1.813 5.76l-1.706-5.76l-1.707 5.76l-1.813-5.76m12.761 4.673c-.326.652-1.087 1.087-1.847 1.087a2.18 2.18 0 0 1-2.174-2.174V30.57a2.18 2.18 0 0 1 2.174-2.174a2.18 2.18 0 0 1 2.173 2.174v.76H22.55m6.63-5.869v7.607c0 .652.434 1.087 1.086 1.087h.326m2.185-7.607v6.52c0 .652.435 1.087 1.087 1.087h.326m-2.608-5.434h2.391");
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

.tro6busfo {
  cx: 10.261px;
  cy: 14.606px;
  r: 0.75px;
  fill: currentColor;
}

.u_n8_pwyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.261 17.057v5.433m2.321-5.433v5.433m.001-3.26a2.18 2.18 0 0 1 2.173-2.173a2.18 2.18 0 0 1 2.173 2.173v3.26m.001-3.26a2.18 2.18 0 0 1 2.173-2.173a2.18 2.18 0 0 1 2.173 2.173v3.26m2.254-5.433v5.433m0-3.26a2.18 2.18 0 0 1 2.174-2.173a2.18 2.18 0 0 1 2.173 2.173v3.26");
}

</style>
