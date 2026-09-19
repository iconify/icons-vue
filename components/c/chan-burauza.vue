<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yt6grqb_c"/><circle class="wybi6tbnj"/><circle class="exo_phbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chan-burauza" /></template>
<style>
.exo_phbpc {
  cx: 15.985px;
  cy: 23.671px;
  r: 3.621px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wybi6tbnj {
  cx: 31.583px;
  cy: 23.671px;
  r: 3.621px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yt6grqb_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.462 24.472c0-2.398.488-4.686 1.6-7.114L4.5 6.156L15.94 9.01C19.148 7.59 21.436 7.1 24 7.1s4.853.489 8.06 1.91L43.5 6.156l-3.561 11.202c1.11 2.428 1.6 4.716 1.6 7.114c0 9.595-7.778 17.372-17.539 17.372S6.462 34.066 6.462 24.472");
}

</style>
