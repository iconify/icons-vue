<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bxwyyacte"/><circle class="hfafpk-vy"/><path class="rx5ne-u1n"/><circle class="r_7r8zbkn"/><path class="uft-wkbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lockito" /></template>
<style>
.bxwyyacte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.107 22.018l5.286-2.643l5.285 2.643v15.857l5.286 2.643l7.928-3.965");
}

.hfafpk-vy {
  cx: 38.535px;
  cy: 35.232px;
  r: 0.991px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r_7r8zbkn {
  cx: 9.464px;
  cy: 23.339px;
  r: 0.991px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rx5ne-u1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.51 19.375a3.964 3.964 0 0 0-3.325 6.083l3.35 7.131l3.378-7.175a3.964 3.964 0 0 0-3.404-6.039");
}

.uft-wkbuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.438 7.483a3.964 3.964 0 0 0-3.324 6.083l3.35 7.13l3.379-7.174a3.964 3.964 0 0 0-3.405-6.04");
}

</style>
