<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ob658d3ok"/><path class="zq4wn24kl"/><path class="sojocjqrm"/><path class="nbot_wkua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:garmin-messenger" /></template>
<style>
.nbot_wkua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.334 22.786H13a2.09 2.09 0 0 0-2.096 2.095v8.381A2.09 2.09 0 0 0 13 35.357h2.095V38.5l4.19-3.143h6.286a2.09 2.09 0 0 0 2.095-2.095v-1.19M12.15 8.15a2.65 2.65 0 1 0-5.3 0v2.7a2.65 2.65 0 1 0 5.3 0H9.5");
}

.ob658d3ok {
  cx: 9.501px;
  cy: 9.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sojocjqrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.43 16.5a2.09 2.09 0 0 0-2.096 2.095v8.381a2.09 2.09 0 0 0 2.095 2.095h6.286l4.19 3.143v-3.143h2.096a2.09 2.09 0 0 0 2.095-2.095v-8.38a2.09 2.09 0 0 0-2.095-2.096z");
}

.zq4wn24kl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.24 5.5H38.5c2.217 0 4 1.784 4 4v29c0 2.216-1.783 4-4 4h-29c-2.215 0-4-1.784-4-4V15.201");
}

</style>
