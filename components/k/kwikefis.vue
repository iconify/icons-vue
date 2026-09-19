<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hyil6lbcw"/><circle class="cpk0fnbgt"/><path class="ftc0p-b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kwikefis" /></template>
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

.ftc0p-b6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.395 24H45.5m-43 0h11.105M24 2.5v2m10.758.885l-1.001 1.732m8.871 6.148l-1.733.999M13.242 5.385l1.001 1.732m-8.871 6.148l1.732.999");
}

.hyil6lbcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.675 30.6v-3.3l-13.2-8.25V9.975a2.475 2.475 0 0 0-4.95 0v9.075l-13.2 8.25v3.3l13.2-4.125v9.075l-3.3 2.475V40.5L24 38.85l5.775 1.65v-2.475l-3.3-2.475v-9.075Z");
}

</style>
