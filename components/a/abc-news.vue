<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m7bqeubzu"/><circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><circle class="kzaxxjc8o"/><circle class="gbye05btj"/><path class="rl4wifl5e"/></g><path class="po1h6nbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:abc-news" /></template>
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

.kzaxxjc8o {
  cx: 12.706px;
  cy: 24px;
  r: 4.5px;
}

.m7bqeubzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.5 24v-9m10.15 18.331l-1.444 4.637l-1.444-4.637l-1.444 4.637l-1.443-4.637m7.244 4.246c.319.268.664.391 1.439.391h.392c.64 0 1.157-.519 1.157-1.16s-.518-1.159-1.157-1.159h-.785a1.158 1.158 0 0 1 0-2.319h.393c.775 0 1.12.124 1.44.392m-16.605 4.246v-2.887a1.75 1.75 0 1 0-3.5 0m0 2.887v-4.637m8.479 3.754a1.75 1.75 0 0 1-3.27-.867v-1.137a1.75 1.75 0 1 1 3.5 0v.568h-3.5");
}

.po1h6nbwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.206 24v4.5");
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
