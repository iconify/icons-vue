<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="v_yabbc2p"/><path class="lhku0co0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iconeration" /></template>
<style>
.lhku0co0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5L45.5 24L24 45.5L2.5 24zm0 6.297v30.406M45.5 24h-6.297M8.797 24H2.5");
}

.v_yabbc2p {
  cx: 24px;
  cy: 24px;
  r: 15.203px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
