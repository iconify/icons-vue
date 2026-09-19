<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ksrzkulwb"/><circle class="laix5fbpb"/><path class="ybfhly8cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:delta-hotspot" /></template>
<style>
.ksrzkulwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 5.5h10v10h-10zm0 27h10v10h-10z");
}

.laix5fbpb {
  cx: 10.5px;
  cy: 24px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ybfhly8cb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 32.5L24 24l8.5-8.5M24 24h-8.5");
}

</style>
