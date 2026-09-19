<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="rh3on3bki"/><path class="bk-ghe5uh"/><path class="m-ziipbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:greenpass" /></template>
<style>
.bk-ghe5uh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.12 28.156l7.83 7.784l15.93-15.748");
}

.m-ziipbfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.561 8.583h9.018a2.88 2.88 0 0 1 2.925 2.7V40.35a3.32 3.32 0 0 1-2.835 3.15H9.331a2.634 2.634 0 0 1-2.835-2.7V11.958c.066-1.67.842-3.29 2.475-3.42l9.442.045h.026A5.49 5.49 0 0 1 24 4.5a5.49 5.49 0 0 1 5.561 4.083");
}

.rh3on3bki {
  cx: 24px;
  cy: 10.467px;
  r: 2.824px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
