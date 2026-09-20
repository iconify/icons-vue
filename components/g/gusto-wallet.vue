<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="fck5o5bmw"/><rect transform="matrix(-1 0 0 -1 23.293 37.946)" class="l1b92y57y"/><rect class="ve8carguq"/><path class="r61ux1bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gusto-wallet" /></template>
<style>
.fck5o5bmw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.793 16.129v6.439a2.146 2.146 0 0 1-2.147 2.146a2.14 2.14 0 0 1-1.517-.628");
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

.l1b92y57y {
  width: 4.293px;
  height: 5.688px;
  x: 9.5px;
  y: 16.129px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.146px;
  ry: 2.146px;
}

.r61ux1bot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.067 16.129v3.541a2.146 2.146 0 1 0 4.293 0v-3.54m0 3.54v2.147m2.508-.48c.392.329.815.48 1.765.48h.482a1.42 1.42 0 0 0 1.419-1.422a1.42 1.42 0 0 0-1.42-1.422h-.962a1.42 1.42 0 0 1-1.42-1.422a1.42 1.42 0 0 1 1.42-1.422h.481c.95 0 1.373.15 1.765.48m2.842-2.251v6.386c0 .592.48 1.073 1.073 1.073h.322m-2.522-5.688h2.254M16.583 27.954l-1.771 5.688l-1.771-5.688l-1.77 5.688L9.5 27.954m15.305-2.898v7.513c0 .592.48 1.073 1.073 1.073h.322m1.636-8.586v7.513c0 .592.48 1.073 1.073 1.073h.322m7.874-7.459v6.386c0 .592.48 1.073 1.073 1.073h.322m-2.522-5.688h2.254m-15.698 3.542a2.146 2.146 0 0 1-4.293 0V30.1a2.146 2.146 0 0 1 4.293 0m0 3.542v-5.688m11.869 4.605a2.146 2.146 0 0 1-4.011-1.063V30.1a2.146 2.146 0 0 1 4.293 0v.698h-4.293");
}

.ve8carguq {
  width: 4.293px;
  height: 5.688px;
  x: 31.865px;
  y: 16.129px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.146px;
  ry: 2.146px;
}

</style>
