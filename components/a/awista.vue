<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jj576nbpc"/><path class="u0mfwddxm"/><path class="opnf7wejj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:awista" /></template>
<style>
.jj576nbpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 22.003S21.106 9.669 4.5 35.439c9.991-9.302 24.944-13.16 36.795-7.786z");
}

.opnf7wejj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.708 21.891v-5.47h12.95v2.65m0 6.2v4.1h-12.95v-2.36");
}

.u0mfwddxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.848 24.211v-11.65h20.67v6.89m0 6.34v7.44h-20.67v-4.7");
}

</style>
