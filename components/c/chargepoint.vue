<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="akkfgpe_c"/><path class="jpnp3ijoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chargepoint" /></template>
<style>
.akkfgpe_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.606 24H5.5m33-18.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jpnp3ijoc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.394 19.394A6.394 6.394 0 0 0 24 13h0a6.394 6.394 0 0 0-6.394 6.394v9.212A6.394 6.394 0 0 0 24 35h0a6.394 6.394 0 0 0 6.394-6.394");
}

</style>
