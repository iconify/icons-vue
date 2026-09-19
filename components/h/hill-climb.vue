<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="sas1m5bri"/><circle class="nrse6bb_u"/><path class="yvkfojb0i"/></g><path class="psdjl9bpm"/><circle class="s28takb6r"/><circle class="sx3-c8bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hill-climb" /></template>
<style>
.nrse6bb_u {
  cx: 35.773px;
  cy: 20.618px;
  r: 5.373px;
}

.psdjl9bpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.627 26.868c-2.569-2.457-6.998-4.251-9.858-4.195");
}

.s28takb6r {
  cx: 35.773px;
  cy: 20.618px;
  r: 1.492px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sas1m5bri {
  cx: 21.592px;
  cy: 34.799px;
  r: 5.373px;
}

.sx3-c8bvz {
  cx: 21.592px;
  cy: 34.799px;
  r: 1.492px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yvkfojb0i {
  d: path("m25.391 31l6.583-6.582m-10.84-13.579l7.882 2.64l5.651-5.651l2.989 1.757l4.575 4.575l-2.659 2.659m-10.556-3.34L8.54 33.955l8.272 5.625l.981-.982");
}

</style>
