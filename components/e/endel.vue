<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="dab7b07ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:endel" /></template>
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

.dab7b07ps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.7 22.6h13.6c3.2 0 4.9-2.4 3.3-5.3c-1-1.9-1-4.1-1-4.1c0-2.9 2.4-5.2 5.3-5.2h.2c2.9 0 5.3 2.4 5.3 5.3s.5 2.3-5.4 10.8c-5.3 7.5-5.4 10.7-5.4 10.7c0 2.9 2.4 5.3 5.3 5.3h.2c2.9 0 5.3-2.3 5.3-5.2s0-2.2-.9-4.1c-1.3-2.5.4-5.1 3.3-5.1h13.6");
}

</style>
