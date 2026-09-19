<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j6dzlpbqz"/><path class="crsmkbbiv"/><ellipse transform="rotate(-42.48 21.66 35.525)" class="croh8jbzf"/><ellipse transform="rotate(-42.48 36.295 35.526)" class="ipgwwsb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:idealo-shopping" /></template>
<style>
.croh8jbzf {
  cx: 21.66px;
  cy: 35.526px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.086px;
  ry: 2.588px;
}

.crsmkbbiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.752 12.453h17.955c.47 0 .838.408.789.876l-1.002 9.55a2.024 2.024 0 0 1-2.012 1.812H22.07m-4.491-8.185H12.07m4.546 6.438H5.5");
}

.ipgwwsb7b {
  cx: 36.295px;
  cy: 35.526px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.086px;
  ry: 2.588px;
}

.j6dzlpbqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.048 29.602H22.615c-.645 0-1.142-.57-1.054-1.21l2.481-18.048a.613.613 0 0 0-.607-.696h-3.5");
}

</style>
