<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lfosdogde"/><circle class="fd3s2kdmk"/><path class="cj2he5-hr"/><path class="jgvleqztb"/><rect class="wppfnbb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:epson-iprojection" /></template>
<style>
.cj2he5-hr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 25.969v-14.5H31v11");
}

.fd3s2kdmk {
  cx: 35.5px;
  cy: 30.718px;
  r: 2.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jgvleqztb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29 22.469v-9h-5.625v9m0-6.456H17.75v6.456m0-4.03h-5.625v4.03m0-1.75H6.5v2.765m0 9.485h5.25m-5.25-2H12m-5.5-2H12m-5.459-2h5.209");
}

.lfosdogde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.9 34.47a3 3 0 0 1-.4-1.501v-5.5c0-1.662 1.338-3 3-3h31c1.662 0 3 1.338 3 3v5.5c0 .548-.145 1.06-.4 1.501zm33.6 2.062h-31");
}

.wppfnbb0j {
  width: 8px;
  height: 6px;
  x: 31.5px;
  y: 26.968px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

</style>
