<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xo4rk-ssf"/><path class="euzqatbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:352life" /></template>
<style>
.euzqatbzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24v21.5M5.379 13.252L24 24l18.621-10.748m-.001 14.337l-12.414 7.164M5.381 27.59l12.414 7.164m18.62-10.749L24.001 31.17l-12.414-7.165m.001-14.334l12.414 7.165m-6.208-10.75l12.414 7.165");
}

.xo4rk-ssf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5L5.38 13.25v21.5L24 45.5l18.62-10.75v-21.5z");
}

</style>
