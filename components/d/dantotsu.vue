<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="tr6uqob4u"/><path class="k-qerkhai"/><path class="j3044sfff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dantotsu" /></template>
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

.j3044sfff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.974 22.763l-6.272-3.621a1.43 1.43 0 0 0-2.143 1.237v7.242c0 1.1 1.19 1.787 2.143 1.237l6.272-3.62a1.43 1.43 0 0 0 0-2.475");
}

.k-qerkhai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.345 9.224H24c8.16 0 14.776 6.616 14.776 14.776S32.16 38.776 24 38.776H8.345");
}

.tr6uqob4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.232 32.467H24a8.467 8.467 0 1 0 0-16.934H4.232");
}

</style>
