<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ygzhvrbcl"/><circle class="uayb89x8a"/><circle class="nw5wotbap"/><circle class="n-rw3fbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lio-occitanie" /></template>
<style>
.n-rw3fbxt {
  cx: 5.988px;
  cy: 32.965px;
  r: 1.488px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nw5wotbap {
  cx: 18.155px;
  cy: 15.035px;
  r: 1.488px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uayb89x8a {
  cx: 33.791px;
  cy: 24.744px;
  r: 9.709px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ygzhvrbcl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.054 14.564v19.889m6.101-14.88v14.582");
}

</style>
