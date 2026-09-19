<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="c5498hiju"/><circle class="i7h7a_b-k"/><circle class="tfqgn2tvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:babydots" /></template>
<style>
.c5498hiju {
  cx: 24.65px;
  cy: 10.95px;
  r: 6.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i7h7a_b-k {
  cx: 13.68px;
  cy: 30.06px;
  r: 6.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tfqgn2tvj {
  cx: 34.32px;
  cy: 37.05px;
  r: 6.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
