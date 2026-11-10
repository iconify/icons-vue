<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="rycrdzd2c"/><path class="ra453ackx"/><circle class="wfyb7rb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kernelsu-next" /></template>
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

.ra453ackx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5c-5.937 0-10.75-4.813-10.75-10.75S18.063 24 24 24s10.75-4.813 10.75-10.75S29.937 2.5 24 2.5");
}

.rycrdzd2c {
  cx: 24px;
  cy: 13.25px;
  r: 2.813px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wfyb7rb9k {
  cx: 24px;
  cy: 34.75px;
  r: 2.813px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
