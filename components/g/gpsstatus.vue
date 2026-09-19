<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nta5t3b4g"/><path class="acdzc82td"/><path class="v7xor1bic"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gpsstatus" /></template>
<style>
.acdzc82td {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.85 43.6a26 26 0 0 0 .2-3.19A25.46 25.46 0 0 0 7.59 15a26 26 0 0 0-3.19.2");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nta5t3b4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.8 25.51a1.78 1.78 0 1 1 0 2.52a1.78 1.78 0 0 1 0-2.52M10.56 37a9.52 9.52 0 0 1 .12-13.44a1.47 1.47 0 0 1 2.08.09l.12.14l11.35 10.93a1.71 1.71 0 0 1 0 2.42a9.58 9.58 0 0 1-13.55 0a1 1 0 0 1-.14-.14Z");
}

.v7xor1bic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.89 37.3c.07-.81.11-1.62.11-2.45A27.85 27.85 0 0 0 13.15 7c-.83 0-1.64 0-2.45.11");
}

</style>
