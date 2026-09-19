<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tm0tovb9i"/><path class="kz6l1filr"/><path class="usaidlbwv"/><path class="u412e5vku"/><path class="o14xn_zlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dotpict" /></template>
<style>
.kz6l1filr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.2 28.4v13h2.6v-2.6H7.6V31h5.2v-5.2h-2.6V15.4h2.6V7.6H18V5h13v2.6h5.2v7.8h2.6v10.4h-2.6V31h5.2v7.8h-5.2v2.6h2.6v-13Z");
}

.o14xn_zlu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.8 29.05v7.15h2.6v5.2");
}

.tm0tovb9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.4 28.4V18h-2.6v7.8h1.95M17.35 18H15.4v10.4");
}

.u412e5vku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.2 41.4V44h-2.6v-2.6Zm2.6 0V44h2.6v-2.6m-7.8 0v-5.2h2.6v-7.15");
}

.usaidlbwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.05 25.8H18V15.4h2.6v5.2h5.2m-5.2 8.45V31H18v5.2h-2.6v5.2h18.2v-5.2H31V31h-2.6v-1.95");
}

</style>
