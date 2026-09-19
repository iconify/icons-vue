<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xx0unqb4j"/><circle class="ayy31cbrt"/><path class="vohn0_9zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hedgecam-2" /></template>
<style>
.ayy31cbrt {
  cx: 24.037px;
  cy: 26.295px;
  r: 8.126px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vohn0_9zp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.402 11.624h6.171l3.937-4.552h11.499l3.344 4.552h6.245a2.896 2.896 0 0 1 2.902 2.902v23.5a2.896 2.896 0 0 1-2.902 2.902H8.402A2.896 2.896 0 0 1 5.5 38.025v-23.5a2.896 2.896 0 0 1 2.902-2.902");
}

.xx0unqb4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.303 32.614a2.76 2.76 0 0 1 2.687-2.79a2.777 2.777 0 0 1 1.963 4.753c-1.137.93-4.65 3.616-4.65 3.616h5.477");
}

</style>
