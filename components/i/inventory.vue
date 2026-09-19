<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzpqnlmob"/><path class="msycuzbnc"/><circle class="stc1_f3um"/><path class="qzy3-t8hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:inventory" /></template>
<style>
.hzpqnlmob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

.msycuzbnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.53 26.22L18.2 13.551L34.449 29.8L21.78 42.47");
}

.qzy3-t8hf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.269 24.482L5.5 22.713m1.769 1.769L5.5 22.713m3.607-.07l-1.768-1.768m3.607-.07l-1.769-1.769m3.607-.07l-1.768-1.768m3.607-.07l-1.769-1.769m3.607-.07l-1.768-1.768m7.219 3.654l1.769-1.769m-1.769 1.769l1.769-1.769m-3.686-.148l1.769-1.769m1.987 5.524l1.769-1.768m.07 3.607l1.768-1.768m.07 3.607l1.769-1.769m.07 3.607l1.768-1.768m.07 3.607l1.769-1.769m.149 3.686l1.768-1.768M25.287 42.5l-1.769-1.769m1.769 1.769l-1.769-1.769m3.607-.07l-1.768-1.768m3.607-.07l-1.769-1.769m3.607-.07l-1.768-1.768m3.607-.07l-1.769-1.769m3.607-.07l-1.768-1.768M21.208 11.861l-2.841-2.842l-2.842 2.842m21.339 20.147l1.801-3.482M11.352 10.695L14.358 10");
}

.stc1_f3um {
  cx: 27.873px;
  cy: 29.84px;
  r: 1.973px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
