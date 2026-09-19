<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="syoxjwvbi"/><path class="c7gs42hof"/><path class="rxf06bcbl"/><circle class="nndkoz9mg"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geocaching" /></template>
<style>
.c7gs42hof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.611 20.336c0-5.425-9.83-7.654-9.83-12.364");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.nndkoz9mg {
  cx: 14.696px;
  cy: 9.234px;
  r: 1.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rxf06bcbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.1 14.1c.204-.174.296-.324.596-.592c2.368-2.118 4.915-3.18 4.915-5.536");
}

.syoxjwvbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5v-37M5.5 24h37M29.614 35.218c3.676-4.073 5.526-.582 8.807-6.05c-4.374.925-6.813-2.187-10.262.379L31.48 42.5M14.1 14.1a13.987 13.987 0 0 0-.999 18.677m19.677-19.675A13.93 13.93 0 0 0 24 10m-8.778 24.899A13.93 13.93 0 0 0 24 38m14-14a13.93 13.93 0 0 0-3.101-8.777");
}

</style>
