<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q_cjpbc7w"/><path class="ui5ls8baj"/><circle class="aote17kja"/><circle class="z1b8mlbil"/><circle class="m28c8179y"/><circle class="h4_erm3ft"/><circle class="gm43ey-je"/><circle class="nt05se3bj"/><circle class="zfhazablz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:3c-app-manager" /></template>
<style>
.aote17kja {
  cx: 32.792px;
  cy: 24px;
  r: 7.325px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gm43ey-je {
  cx: 32.792px;
  cy: 22.5px;
  r: 0.75px;
  fill: currentColor;
}

.h4_erm3ft {
  cx: 35.792px;
  cy: 25.5px;
  r: 0.75px;
  fill: currentColor;
}

.m28c8179y {
  cx: 29.792px;
  cy: 25.5px;
  r: 0.75px;
  fill: currentColor;
}

.nt05se3bj {
  cx: 29.792px;
  cy: 22.5px;
  r: 0.75px;
  fill: currentColor;
}

.q_cjpbc7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 28.826v.12c0 5.361-4.346 9.707-9.708 9.707h0c-5.361 0-9.708-4.346-9.708-9.707v-9.892c0-5.361 4.347-9.707 9.708-9.707h0c5.362 0 9.708 4.346 9.708 9.707v.12M5.503 36.181c2.023 1.696 4.208 2.472 9.113 2.472h1.143a7.325 7.325 0 0 0 7.325-7.325h0a7.325 7.325 0 0 0-7.325-7.325");
}

.ui5ls8baj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 11.794c2.028-1.69 4.214-2.46 9.12-2.447l1.14.006a7.325 7.325 0 0 1 7.324 7.325h0a7.325 7.325 0 0 1-7.325 7.325m-5.63 0h5.63");
}

.z1b8mlbil {
  cx: 32.792px;
  cy: 25.5px;
  r: 0.75px;
  fill: currentColor;
}

.zfhazablz {
  cx: 35.792px;
  cy: 22.5px;
  r: 0.75px;
  fill: currentColor;
}

</style>
