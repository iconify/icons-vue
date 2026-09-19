<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="h2s9k9bqy"/><path class="rwf38yblb"/><path class="axcnbfdgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huckleberry" /></template>
<style>
.axcnbfdgy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11.767a5.6 5.6 0 0 0-5.602-5.602H5.5a5.6 5.6 0 0 0 5.603 5.602z");
}

.h2s9k9bqy {
  cx: 24px;
  cy: 26.801px;
  r: 15.034px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rwf38yblb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11.767a5.6 5.6 0 0 1 5.603-5.602H42.5a5.6 5.6 0 0 1-5.602 5.602z");
}

</style>
