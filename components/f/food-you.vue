<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l7i9bhbmf"/><ellipse class="fw7k9qbef"/><ellipse class="qj4mh036m"/><circle class="a-qj6ju3g"/><circle class="mu36-mb6i"/><path class="yhs58v74n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:food-you" /></template>
<style>
.a-qj6ju3g {
  cx: 18.25px;
  cy: 26px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fw7k9qbef {
  cx: 24px;
  cy: 13.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 14.5px;
  ry: 4.5px;
}

.l7i9bhbmf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.972 36.406C39.995 39.904 32.699 42.5 24 42.5c-8.698 0-15.995-2.596-17.972-6.094c-.537-.95-.528-2.801-.528-3.906v-17c0-1.104-.01-2.955.528-3.906C8.005 8.096 15.301 5.5 24 5.5s15.995 2.596 17.972 6.095c.537.95.528 2.8.528 3.905v17c0 1.105.01 2.955-.528 3.906");
}

.mu36-mb6i {
  cx: 29.75px;
  cy: 26px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qj4mh036m {
  cx: 24px;
  cy: 13.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.5px;
  ry: 2px;
}

.yhs58v74n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.5a8 3 0 0 0-3.754.352A4 4 0 0 0 24 34.5a4 4 0 0 0 3.754-2.648A8 3 0 0 0 24 31.5");
}

</style>
