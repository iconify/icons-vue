<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g06o4rb3m"/><circle class="up-1r882j"/><path class="lk0wlagfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:guessthatpokemon" /></template>
<style>
.g06o4rb3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24m43 0c0-11.874-9.626-21.5-21.5-21.5S2.5 12.126 2.5 24");
}

.lk0wlagfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24H29.375M2.5 24h16.125");
}

.up-1r882j {
  cx: 24px;
  cy: 24px;
  r: 5.375px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
