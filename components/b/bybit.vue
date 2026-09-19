<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2f6iwb0z"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bybit" /></template>
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

.n2f6iwb0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.096 17.056v9.258m2.271-6.943H40.5m-3.067 9.258v-9.258m-16.143 0L18.224 24l-3.067-4.629m3.067 9.258V24m-6.905 0a2.315 2.315 0 1 1 0 4.629H7.5v-9.258h3.819a2.315 2.315 0 1 1 0 4.629m0 0H7.5m19.88 0a2.315 2.315 0 1 1 0 4.629h-3.819v-9.258h3.819a2.315 2.315 0 1 1 0 4.629m0 0h-3.819");
}

</style>
