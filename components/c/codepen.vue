<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y7gylibrs"/><path class="l4l7ocbqe"/><path class="w22dvxbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:codepen" /></template>
<style>
.l4l7ocbqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 30.005L24 17.995l18.5 12.01");
}

.w22dvxbqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 17.996L24 30.006l18.5-12.01M24 42.015v-12.01m0-12.01V5.985");
}

.y7gylibrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.015L5.5 30.005v-12.01L24 5.985l18.5 12.01v12.01z");
}

</style>
