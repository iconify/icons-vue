<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="c0s01yjaw"/><path class="l_4ldhbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:espresso-house" /></template>
<style>
.c0s01yjaw {
  cx: 24px;
  cy: 24px;
  r: 13.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l_4ldhbjj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 23.6h7.6m1 5.6h-8m41.8 0h-8m1-5.6h7.6m-12.4 5.1c.1 2.2-6.4 3.2-11.8.4c-4.7-2.4-7.4-4.6-7.4-7.9s6-5.5 11.8-3.7c7.5 2.2 8.1 8.7 8.1 8.7c-6.1-8.2-13.1-6.7-13.1-6.7c6.9 1.8 12.3 6.4 12.4 9.2");
}

</style>
