<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><circle class="kzaxxjc8o"/><circle class="gbye05btj"/><path class="rl4wifl5e"/></g><path class="i9y3oubse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:abc-family" /></template>
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

.gbye05btj {
  cx: 24px;
  cy: 24px;
  r: 4.5px;
}

.i9y3oubse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.5 24v-9m5.353 20.08a1.75 1.75 0 1 1 3.5 0v2.888m-3.5-4.637v4.637m3.5-2.888a1.75 1.75 0 1 1 3.5 0v2.888m-8.751-1.75a1.75 1.75 0 1 1-3.5 0v-1.137a1.75 1.75 0 1 1 3.5 0m0 2.887v-4.637m-5.917 4.637v-5.775c0-.676.548-1.225 1.225-1.225c.603 0 .98.179 1.237.513m-3.5 1.85h2.45M17.206 24v4.5");
}

.kzaxxjc8o {
  cx: 12.706px;
  cy: 24px;
  r: 4.5px;
}

.rl4wifl5e {
  d: path("M39.325 26.002a4.5 4.5 0 1 1 0-4.003");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
