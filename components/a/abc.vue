<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><circle class="kzaxxjc8o"/><circle class="gbye05btj"/><path class="rl4wifl5e"/></g><path class="gfcrq_3sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:abc" /></template>
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

.gfcrq_3sa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.206 24v4.5M19.5 24v-9");
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
