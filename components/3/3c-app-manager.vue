<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i53ncf72s"/><path class="ipta0ih0a"/><circle class="aote17kja"/><circle class="z1b8mlbil"/><circle class="m28c8179y"/><circle class="h4_erm3ft"/><circle class="gm43ey-je"/><circle class="nt05se3bj"/><circle class="zfhazablz"/>`;
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

.i53ncf72s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 28.826v.12c0 5.361-4.346 9.707-9.708 9.707c-5.361 0-9.708-4.346-9.708-9.707v-9.892c0-5.361 4.347-9.707 9.708-9.707c5.362 0 9.708 4.346 9.708 9.707v.12");
}

.ipta0ih0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.503 36.181c2.023 1.696 4.208 2.472 9.113 2.472h1.143a7.325 7.325 0 1 0 0-14.65M5.5 11.794c2.028-1.69 4.214-2.46 9.12-2.447l1.14.006a7.325 7.325 0 1 1 0 14.65m-5.631 0h5.63");
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
