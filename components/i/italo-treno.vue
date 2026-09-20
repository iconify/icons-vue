<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="f1yts4yvh"/><path class="m-_60zbkq"/><circle class="looa8h7tw"/><path class="ehw52cklp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:italo-treno" /></template>
<style>
.ehw52cklp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.396 21.814v7.961m23.1 0za3.013 3.013 0 0 1-3.004-3.004v-1.953a3.013 3.013 0 0 1 3.004-3.004a3.013 3.013 0 0 1 3.004 3.004v1.953a3.013 3.013 0 0 1-3.004 3.004");
}

.f1yts4yvh {
  cx: 10.201px;
  cy: 29.541px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.looa8h7tw {
  cx: 12.396px;
  cy: 19.494px;
  r: 0.75px;
  fill: currentColor;
}

.m-_60zbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.673 26.77a3.013 3.013 0 0 1-3.004 3.005a3.013 3.013 0 0 1-3.004-3.004v-1.953a3.013 3.013 0 0 1 3.004-3.004a3.013 3.013 0 0 1 3.004 3.004m0 4.957v-7.961m3.004-4.056v10.514c0 .901.601 1.502 1.502 1.502h.451M16.661 19.26v10.515m-1.652-7.961h3.154");
}

</style>
