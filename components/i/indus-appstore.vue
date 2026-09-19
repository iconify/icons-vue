<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="q1iwh3a2p"/><path class="idj2lppny"/><path class="jj1nd9bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:indus-appstore" /></template>
<style>
.idj2lppny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.816 19.895L24 24.514l7.184-4.619v7.185L24 31.698l-7.184-4.618z");
}

.jj1nd9bus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.816 31.697L24 36.316l7.184-4.619v7.185L24 43.5l-7.184-4.618z");
}

.q1iwh3a2p {
  cx: 24px;
  cy: 11.684px;
  r: 7.184px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
