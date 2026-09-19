<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="t1mfal-np"/><path class="ynx9m2bpq"/><path class="lnqxs73ma"/><path class="qzmyunh-t"/><path class="zdze1ib3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:discogs" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lnqxs73ma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.5A16.5 16.5 0 0 0 7.5 24");
}

.qzmyunh-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13a11 11 0 0 0-11 11m11 16.5A16.5 16.5 0 0 0 40.5 24");
}

.t1mfal-np {
  cx: 24px;
  cy: 24px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ynx9m2bpq {
  fill: currentColor;
  d: path("M24.75 24a.75.75 0 1 1-.75-.75a.76.76 0 0 1 .75.75");
}

.zdze1ib3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 35a11 11 0 0 0 11-11");
}

</style>
