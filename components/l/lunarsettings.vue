<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wv21wkb3s"/><path class="qbec7vbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lunarsettings" /></template>
<style>
.qbec7vbmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.998 45.5a21.5 21.5 0 0 1 0-43z");
}

.wv21wkb3s {
  cx: 24px;
  cy: 24px;
  r: 11.727px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
