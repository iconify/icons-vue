<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="kuxwdpzmt"/><ellipse class="bq8gd4bzj"/><ellipse class="e846qoojt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asana" /></template>
<style>
.bq8gd4bzj {
  cx: 34.7px;
  cy: 33.42px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.8px;
  ry: 7.71px;
}

.e846qoojt {
  cx: 24px;
  cy: 14.58px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.8px;
  ry: 7.71px;
}

.kuxwdpzmt {
  cx: 13.3px;
  cy: 33.42px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.8px;
  ry: 7.71px;
}

</style>
