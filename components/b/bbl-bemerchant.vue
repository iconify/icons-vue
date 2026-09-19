<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="m41v7ivju"/><path class="f1y1auf-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bbl-bemerchant" /></template>
<style>
.f1y1auf-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.096 26.853c-.326 2.574 4.075 5.918 4.906 7.423m-3.86-22.094c0 2.05 1.65 3.7 3.7 3.7h.266c2.05 0 3.7-1.65 3.7-3.7V5.5m-15.334 6.682c0 2.05 1.65 3.7 3.7 3.7h.267c2.05 0 3.7-1.65 3.7-3.7V5.5m7.666 6.682c0 2.05 1.65 3.7 3.7 3.7h.267c2.05 0 3.7-1.65 3.7-3.7V5.5M5.5 14.341a3.69 3.69 0 0 0 3.008 1.54h.267c2.05 0 3.7-1.65 3.7-3.7V5.502m22.999 6.68c0 2.05 1.65 3.7 3.7 3.7h.266a3.69 3.69 0 0 0 3.06-1.615");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.m41v7ivju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.906 26.855c.326 2.574-4.075 5.918-4.906 7.423v3.659c-2.976-2.61-9.6-4.675-5.168-10.913L24 19.946l5.168 7.078c4.433 6.238-2.192 8.303-5.168 10.913");
}

</style>
