<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nvt70objd"/><circle class="qboi4lm1i"/><circle class="wim2cdc2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brain-dots" /></template>
<style>
.nvt70objd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8 29.674c4.391 4.208 10.11 6.524 16.032 6.491C29.954 36.133 35.65 33.755 40 29.5");
}

.qboi4lm1i {
  cx: 13.395px;
  cy: 16.555px;
  r: 4.72px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wim2cdc2i {
  cx: 34.605px;
  cy: 16.555px;
  r: 4.72px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
