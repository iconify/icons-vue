<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qebwyhc6s"/><circle class="bjqcvvbkj"/><path class="dceu6bmpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:artm-chrono" /></template>
<style>
.bjqcvvbkj {
  cx: 24px;
  cy: 18.788px;
  r: 9.961px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dceu6bmpt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.788v-6.739m0 6.739l3.784 3.784");
}

.qebwyhc6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.288 18.788C38.288 32.126 24 43.5 24 43.5S9.712 32.126 9.712 18.788C9.712 10.897 16.11 4.5 24 4.5s14.288 6.397 14.288 14.288");
}

</style>
