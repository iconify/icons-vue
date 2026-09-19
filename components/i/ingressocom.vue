<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l7u2q58qa"/><circle class="n7c_i7bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ingressocom" /></template>
<style>
.l7u2q58qa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.285 17.669h9.43V44.5h-2.723a6.71 6.71 0 0 1-6.707-6.708z");
}

.n7c_i7bpx {
  cx: 24px;
  cy: 8.215px;
  r: 4.715px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
