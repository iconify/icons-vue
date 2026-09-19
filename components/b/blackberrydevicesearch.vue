<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo96pw3fy"/><circle class="rcagigcsg"/><path class="lpthb0_iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blackberrydevicesearch" /></template>
<style>
.lpthb0_iz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.76 11.73l-.76 3.5h2.77c2.16 0 2.78-1 2.78-2c0-.67-.41-1.52-2.14-1.52Zm7.17 0l-.76 3.49h2.77c2.17 0 2.78-1 2.78-2c0-.67-.41-1.52-2.14-1.52Zm6.53 3.13l-.76 3.49h2.77c2.17 0 2.79-1 2.79-2c0-.67-.41-1.52-2.14-1.52ZM19.8 17l-.75 3.5h2.77c2.16 0 2.78-1 2.78-2c0-.67-.41-1.52-2.14-1.52Zm7.2 0l-.76 3.5H29c2.17 0 2.78-1 2.78-2c0-.67-.41-1.52-2.13-1.52Zm6.43 3.34l-.76 3.5h2.77c2.17 0 2.78-1 2.78-2c0-.67-.41-1.52-2.13-1.52Zm-7.49 2.13L25.18 26H28c2.17 0 2.78-1 2.78-2c0-.67-.41-1.52-2.13-1.52Z");
}

.rcagigcsg {
  cx: 29.15px;
  cy: 18.85px;
  r: 13.85px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uo96pw3fy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18 27L5 40l3 3l13-13");
}

</style>
