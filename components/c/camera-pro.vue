<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zyxhuxbbz"/><circle class="g2ql4oemh"/><circle class="h6egd8b1q"/><path class="lmehvs21g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:camera-pro" /></template>
<style>
.g2ql4oemh {
  cx: 38.5px;
  cy: 17.02px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h6egd8b1q {
  cx: 24px;
  cy: 25.42px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lmehvs21g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.452 21.172h-4.904l-2.453 4.248l2.453 4.247h4.904l2.453-4.247zm2.453 4.248l2.458 4.258m-14.72-8.506l2.452 4.248M24 16.92l-2.452 4.252m4.904 8.495L24 33.92m-2.452-4.253h-4.912m9.816-8.495h4.911");
}

.zyxhuxbbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 12.02h-8l-2.594-4h-9.812l-2.594 4h-8a4 4 0 0 0-4 4v18.8a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4v-18.8a4 4 0 0 0-4-4");
}

</style>
