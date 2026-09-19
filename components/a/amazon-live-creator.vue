<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="bny0hjdat"/><path class="rre51wbbm"/><circle class="cbm65e-1p"/><path class="wz47lkbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amazon-live-creator" /></template>
<style>
.bny0hjdat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.281 29.406c1.112-.451 3.092-1.05 3.687-.327c.645.781-.17 2.477-.92 3.794");
}

.cbm65e-1p {
  cx: 19.65px;
  cy: 17.675px;
  r: 0.75px;
  fill: currentColor;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rre51wbbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.798 29.928c1.759 1.397 6.953 3.534 12.488 3.534a17 17 0 0 0 10.167-3.079");
}

.wz47lkbdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.65 20.125v5.3m11.738-1.009a2 2 0 0 1-1.738 1.01a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2a2 2 0 0 1 2 2v.65h-4m-11.3-5.351v7a1 1 0 0 0 1 1h.3m4-5.3l2 5.3l2-5.3");
}

</style>
