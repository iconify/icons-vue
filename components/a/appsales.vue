<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vbpw87bxq"/><circle class="atjl5wbbb"/><path class="wrgql63bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:appsales" /></template>
<style>
.atjl5wbbb {
  cx: 34.021px;
  cy: 34.984px;
  r: 7.516px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vbpw87bxq {
  cx: 13.979px;
  cy: 13.016px;
  r: 7.516px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wrgql63bd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.973 42.5l26.054-37");
}

</style>
