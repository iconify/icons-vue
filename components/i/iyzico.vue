<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="e46mm8bgz"/><path class="phohhro8v"/><circle class="nofow-7zg"/><path class="yqn8f46-d"/><circle class="sy0f5ibrh"/><path class="gkjf-jp8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iyzico" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e46mm8bgz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.8 25.056v3.127a2.323 2.323 0 0 1-2.318 2.317c-.695 0-1.274-.232-1.621-.695");
}

.gkjf-jp8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.943 21.117v5.992");
}

.nofow-7zg {
  cx: 9.732px;
  cy: 18.348px;
  r: 0.75px;
  fill: currentColor;
}

.phohhro8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.8 21.117v3.823c0 1.274-1.043 2.317-2.318 2.317s-2.316-1.043-2.316-2.317v-3.823m24.689 5.992a2.27 2.27 0 0 1-2.261-2.261v-1.47a2.27 2.27 0 0 1 2.26-2.26h0a2.27 2.27 0 0 1 2.262 2.26v1.47a2.27 2.27 0 0 1-2.261 2.26m-17.788-5.991h4.438l-4.438 5.992h4.438");
}

.sy0f5ibrh {
  cx: 25.943px;
  cy: 18.348px;
  r: 0.75px;
  fill: currentColor;
}

.yqn8f46-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.732 21.117v5.992m22.772-1.131c-.339.679-1.13 1.13-1.921 1.13h0a2.27 2.27 0 0 1-2.261-2.26v-1.47a2.27 2.27 0 0 1 2.26-2.26h0c.792 0 1.583.452 1.922 1.13");
}

</style>
