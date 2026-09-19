<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aq7674bbl"/><path class="r4w2p_vbf"/><path class="fsijd33uc"/><path class="e7qapkbzu"/><circle class="y6mu6pb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:event-radar" /></template>
<style>
.aq7674bbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.985 13.23c-.014.312-.047.619-.047.934a19.97 19.97 0 0 0 32.124 15.87Zm15.905 8.332l1.32-2.303");
}

.e7qapkbzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.004 16.567a5.725 5.725 0 0 0-8.146-4.423");
}

.fsijd33uc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.517 16.11a9.27 9.27 0 0 0-13.19-7.161");
}

.r4w2p_vbf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.31 33.83S24 37.99 27.2 43.5H10.07a89 89 0 0 0 5.071-13.969M39.03 15.654a12.813 12.813 0 0 0-18.233-9.9");
}

.y6mu6pb2l {
  cx: 25.744px;
  cy: 18.328px;
  r: 1.077px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
