<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="p7sh5zbbb"/><path class="yfikv21vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:azkari" /></template>
<style>
.p7sh5zbbb {
  cx: 24px;
  cy: 29.5px;
  r: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yfikv21vp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.983 22.167L24 29.5l-4.983-7.333M24 36.833V29.5m-4.701 0h9.402m-9.402 3.666h9.402M17 17.376V11.5c0-3.878 3.122-7 7-7s7 3.122 7 7v5.876");
}

</style>
