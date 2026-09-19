<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d8vc0kb2l"/><path class="svu4nvuvp"/><path class="ocedlpbli"/><circle class="lb7dnrn6m"/><path class="f-yv5dbji"/><circle class="ezr7vpbsy"/><path class="as9qxybcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flash-deck" /></template>
<style>
.as9qxybcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.263 11.414a2.2 2.2 0 1 1 4.4 0a1.97 1.97 0 0 1-.645 1.555c-.455.365-1.563.964-1.563 1.895");
}

.d8vc0kb2l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.278 4.5h20.37v33.926h-20.37z");
}

.ezr7vpbsy {
  cx: 21.463px;
  cy: 17.213px;
  r: 0.75px;
  fill: currentColor;
}

.f-yv5dbji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.463 24.405v5.95");
}

.lb7dnrn6m {
  cx: 21.463px;
  cy: 32.405px;
  r: 0.75px;
  fill: currentColor;
}

.ocedlpbli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.185 9.574h2.537V43.5h-20.37v-2.537");
}

.svu4nvuvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.648 7.037h2.537v33.926h-20.37v-2.537");
}

</style>
