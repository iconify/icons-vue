<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s15gkwbmm"/><circle class="c8c-a65gx"/><path class="mi8i40bso"/><circle class="ulj8vpxdd"/><path class="l3oxt9bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:garmin-explore" /></template>
<style>
.c8c-a65gx {
  cx: 9.5px;
  cy: 9.433px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l3oxt9bbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.038 31.227l-4.973-7.517l-5.391 8.245m-11.713-.728l7.431-11.049l5.79 9.218");
}

.mi8i40bso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.176 8.115a2.68 2.68 0 0 0-2.82-2.678c-1.447.076-2.532 1.377-2.532 2.83v2.484A2.68 2.68 0 0 0 9.5 13.433c1.478 0 2.676-1.2 2.676-2.682H9.5");
}

.s15gkwbmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 15.176V38.5a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4H15.291");
}

.ulj8vpxdd {
  cx: 24px;
  cy: 28px;
  r: 11.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
