<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="p1xdd67xq"/><circle class="z4mprac6c"/><circle class="tslcedbhj"/><circle class="xeg823w5g"/><circle class="aor1bebyh"/><circle class="uply_bb6q"/><path class="wcr_5wb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kijiji-autos" /></template>
<style>
.aor1bebyh {
  cx: 32.818px;
  cy: 11.044px;
  r: 0.75px;
  fill: currentColor;
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.p1xdd67xq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.482 13.201v8.582a2.44 2.44 0 0 1-2.429 2.452");
}

.tslcedbhj {
  cx: 22.482px;
  cy: 11.044px;
  r: 0.75px;
  fill: currentColor;
}

.uply_bb6q {
  cx: 37.986px;
  cy: 11.044px;
  r: 0.75px;
  fill: currentColor;
}

.wcr_5wb-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.315 13.201v6.498m10.335-6.498v6.498m5.168-6.498v8.173c0 1.355-1.087 2.453-2.429 2.453m7.597-10.626v6.498M9.264 9.988v9.808m.001-2.084l4.439-4.418m-3.026 3.012l3.49 3.475m-.43 16.111h-2.836m-.702 2.119l2.12-6.4l2.12 6.4m1.6-6.4v4.28a2.12 2.12 0 1 0 4.24 0v-4.28m1.6 0h4.24m-2.12 6.4v-6.4m5.84 0zc1.17 0 2.12.95 2.12 2.12v2.16a2.12 2.12 0 0 1-4.24 0v-2.16c0-1.17.95-2.12 2.12-2.12m3.847 5.699c.393.511.885.702 1.57.702h.947c.881 0 1.596-.715 1.596-1.597v-.007c0-.882-.714-1.596-1.596-1.596h-1.046a1.6 1.6 0 0 1-1.598-1.599c0-.884.717-1.601 1.602-1.601h.942c.685 0 1.177.19 1.57.7M8 28.611h32");
}

.xeg823w5g {
  cx: 27.65px;
  cy: 11.044px;
  r: 0.75px;
  fill: currentColor;
}

.z4mprac6c {
  cx: 17.315px;
  cy: 11.044px;
  r: 0.75px;
  fill: currentColor;
}

</style>
