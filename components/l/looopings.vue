<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ue4vj2ylz"/><circle class="eoz_i9lrw"/><circle class="fdbmobc0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:looopings" /></template>
<style>
.eoz_i9lrw {
  cx: 24px;
  cy: 24px;
  r: 6.833px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fdbmobc0r {
  cx: 37.667px;
  cy: 24px;
  r: 6.833px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ue4vj2ylz {
  cx: 10.333px;
  cy: 24px;
  r: 6.833px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
