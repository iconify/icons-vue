<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ahpy00bqr"/><path class="tf59xlbge"/><circle class="howgxka1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:budgetbakers-wallet" /></template>
<style>
.ahpy00bqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.451 29.914v5.893a3.946 3.946 0 0 1-3.946 3.947H8.446A3.946 3.946 0 0 1 4.5 35.807V12.193a3.946 3.946 0 0 1 3.947-3.947h30.058a3.946 3.946 0 0 1 3.946 3.947v6.098");
}

.howgxka1r {
  cx: 32.458px;
  cy: 24.171px;
  r: 2.705px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tf59xlbge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.294 29.925H31.925a5.822 5.822 0 0 1 0-11.645h10.37c.665 0 1.205.54 1.205 1.206v9.234c0 .665-.54 1.205-1.206 1.205");
}

</style>
