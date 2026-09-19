<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w_-gnybnl"/><path class="n_pd5hbro"/><circle class="d9uqrrb8j"/><circle class="htky4dbhb"/><circle class="so_bb_0gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:codes-rousseau-eleve" /></template>
<style>
.d9uqrrb8j {
  cx: 9.98px;
  cy: 12.141px;
  r: 4.48px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.htky4dbhb {
  cx: 9.98px;
  cy: 24px;
  r: 4.48px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n_pd5hbro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 40.34l-7.959-8.803a7.959 7.959 0 1 0 0-15.917h-7.958");
}

.so_bb_0gu {
  cx: 9.98px;
  cy: 35.859px;
  r: 4.48px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w_-gnybnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.541 23.578h-7.959a7.959 7.959 0 1 1 0-15.917h7.959");
}

</style>
