<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wgemk8bgz"/><circle class="cpk0fnbgt"/><path class="d7gw8tasp"/><path class="dwlzu48ry"/><path class="x5prz9bat"/><path class="uml2gvbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:homey" /></template>
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

.d7gw8tasp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.72 32.72c7.203-7.202 7.203-18.88 0-26.083a18.4 18.4 0 0 0-5.846-3.946");
}

.dwlzu48ry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.28 32.72c7.202 7.203 18.88 7.203 26.083 0a18.4 18.4 0 0 0 3.946-5.846");
}

.uml2gvbah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.72 15.28c-7.202-7.203-18.88-7.203-26.083 0a18.4 18.4 0 0 0-3.946 5.846");
}

.wgemk8bgz {
  cx: 24px;
  cy: 24px;
  r: 12.332px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x5prz9bat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.28 15.28c-7.203 7.202-7.203 18.88 0 26.083a18.4 18.4 0 0 0 5.846 3.946");
}

</style>
