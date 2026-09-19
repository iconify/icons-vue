<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><path class="dvx6lmvtv"/><path class="okoy1ti4k"/><path class="fmb-yf2fz"/></g><g class="y9tr6bcfx"><path class="e5hlgjbsh"/><circle class="x5hnms_va"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hermit-unlocker" /></template>
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

.dvx6lmvtv {
  d: path("M2.708 21c13.366.112 24.18 10.926 24.291 24.292");
}

.e5hlgjbsh {
  d: path("M23.794 33.375H29.5a1 1 0 0 0 1-1v-9a1 1 0 0 0-1-1h-11a1 1 0 0 0-1 1v2.753m2-3.753v-3.25a4.5 4.5 0 1 1 9 0");
}

.fmb-yf2fz {
  d: path("M3.87 31.566c6.638.644 11.92 5.926 12.564 12.565");
}

.okoy1ti4k {
  d: path("M2.616 26.25c10.54.063 19.071 8.594 19.134 19.134");
}

.x5hnms_va {
  cx: 24px;
  cy: 27.875px;
  r: 1.75px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
