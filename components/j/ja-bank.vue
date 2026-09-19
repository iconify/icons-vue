<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="pz6hezbdf"/><path class="m82gsdb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ja-bank" /></template>
<style>
.m82gsdb9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.098 13L12.696 34.5h5.134l12.835-17.917zm5.134 7.167L22.964 34.5h5.134l5.134-7.167l5.134 7.167H43.5z");
}

.pz6hezbdf {
  cx: 8.25px;
  cy: 31.25px;
  r: 3.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
