<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u9nx2c5pa"/><circle class="f1hw8re3h"/><path class="df3p4umbp"/><path class="hcnugvbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iheartradio" /></template>
<style>
.df3p4umbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.402 17.056A10.536 10.536 0 0 0 24 12.976A10.535 10.535 0 1 0 8.645 26.881h-.018l13.978 13.136a2 2 0 0 0 2.739 0l13.848-13.014a10.52 10.52 0 0 0 4.21-9.948");
}

.f1hw8re3h {
  cx: 24px;
  cy: 20.084px;
  r: 3.019px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hcnugvbex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.322 23.734a7.31 7.31 0 0 0 0-7.3m3.668 9.418a11.55 11.55 0 0 0 0-11.535m-16.312 2.117a7.31 7.31 0 0 0 0 7.3m-3.668-9.417a11.55 11.55 0 0 0 0 11.535");
}

.u9nx2c5pa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 40.56V26.523");
}

</style>
