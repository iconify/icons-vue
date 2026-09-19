<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sz1hoeb8u"/><path class="bby09rbdy"/><circle class="g8ksnqo6t"/><path class="m10yfib-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jiocareers" /></template>
<style>
.bby09rbdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.609 5.5h27.066v33.629");
}

.g8ksnqo6t {
  cx: 22.088px;
  cy: 15.017px;
  r: 3.848px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m10yfib-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.11 29.58h12.502m-.001 0c.527-.127 1.172-.283 1.322-1.427s-.135-3.29-1.515-5.005s-3.856-3-6.37-2.946c-2.513.054-5.063 1.446-6.42 3.2s-1.516 3.87-1.237 4.96c.28 1.09.999 1.154 1.718 1.218");
}

.sz1hoeb8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.325 9.145h27.796V42.5H8.325zm4.647 24.971h18.592M13.112 38.87h18.591");
}

</style>
