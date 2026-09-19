<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xnw2u3bma"/><circle class="j1szlyojs"/><circle class="dwnarrmma"/><circle class="azcrfobrz"/><path class="bijx1xm1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:home-assistant" /></template>
<style>
.azcrfobrz {
  cx: 14.853px;
  cy: 32.517px;
  r: 2.944px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bijx1xm1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 25.766v15.898m-7.066-7.066L24 41.664m0-3.533l7.066-7.065");
}

.dwnarrmma {
  cx: 33.147px;
  cy: 28.984px;
  r: 2.944px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j1szlyojs {
  cx: 24px;
  cy: 22.822px;
  r: 2.944px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xnw2u3bma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.53 21.37L26.03 7.127a3 3 0 0 0-4.06 0L6.47 21.371a3 3 0 0 0-.97 2.209v16.084a2 2 0 0 0 2 2h33a2 2 0 0 0 2-2V23.579a3 3 0 0 0-.97-2.209");
}

</style>
