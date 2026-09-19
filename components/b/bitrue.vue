<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wyvzq4ewy"/><circle class="awad51qaz"/><path class="g-4ytyt1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitrue" /></template>
<style>
.awad51qaz {
  cx: 24px;
  cy: 27.239px;
  r: 6.95px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g-4ytyt1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.05 14.916v12.323");
}

.wyvzq4ewy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29 40.613l11.887-6.863v-19.5M7.113 20.024V33.75L24 43.5m11.887-32.137L24 4.5L7.113 14.25");
}

</style>
