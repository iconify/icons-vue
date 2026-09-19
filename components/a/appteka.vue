<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-45 24 24)" class="qzln-5bql"/><path class="xj3_aibxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:appteka" /></template>
<style>
.qzln-5bql {
  width: 43.916px;
  height: 20.269px;
  x: 2.042px;
  y: 13.866px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.134px;
  ry: 10.134px;
}

.xj3_aibxa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.303 36.322l15.009-15.01l9.853 9.854");
}

</style>
