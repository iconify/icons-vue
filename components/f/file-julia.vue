<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><g class="y9tr6bcfx"><circle class="f4n0149th"/><circle class="dswm50_9a"/><circle class="n00v75s8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:file-julia" /></template>
<style>
.dswm50_9a {
  cx: 30.307px;
  cy: 35.09px;
  r: 3.91px;
}

.f4n0149th {
  cx: 17.693px;
  cy: 35.09px;
  r: 3.91px;
}

.n00v75s8t {
  cx: 24px;
  cy: 23.91px;
  r: 3.91px;
}

.r4h1y5b9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
