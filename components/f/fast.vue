<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfytbab4c"/><path class="u43l6sqcb"/><circle class="u4m4-ov0w"/><path class="fadcgle0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fast" /></template>
<style>
.fadcgle0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 30.327V14.786");
}

.u43l6sqcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.914 32.609A13.914 13.914 0 0 0 24 18.695m7.633 13.914A7.633 7.633 0 0 0 24 24.976");
}

.u4m4-ov0w {
  cx: 24px;
  cy: 32.609px;
  r: 2.282px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vfytbab4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.193 32.609H43.5a19.5 19.5 0 0 0-39 0h3.308");
}

</style>
