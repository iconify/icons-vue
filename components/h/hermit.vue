<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><path class="dvx6lmvtv"/><path class="okoy1ti4k"/><path class="fmb-yf2fz"/></g><path class="fl149cchz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hermit" /></template>
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

.fl149cchz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.4 22.4h3.2v3.2h-3.2zm6 0h3.2v3.2h-3.2zm-6 8.806V28.4h3.2v3.2h-2.922m5.722-3.2h3.2v3.2h-3.2zm-6-12h3.2v3.2h-3.2zm6 0h3.2v3.2h-3.2zm-12 0h3.2v3.2h-3.2zm0 8.922V22.4h3.2v3.2h-2.806");
}

.fmb-yf2fz {
  d: path("M3.87 31.566c6.638.644 11.92 5.926 12.564 12.565");
}

.okoy1ti4k {
  d: path("M2.616 26.25c10.54.063 19.071 8.594 19.134 19.134");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
