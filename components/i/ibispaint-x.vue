<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zgfh01w5b"/><path class="du8svlrha"/><circle class="v03br_b0w"/><path class="h4_bf_b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ibispaint-x" /></template>
<style>
.du8svlrha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.375 31.957V39.5a4 4 0 0 1-8 0V19m-7 23.5V22");
}

.h4_bf_b_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.875 25.5v8m-4.596-9.904l-5.657 5.657M21.375 19h-8m9.904-4.596l-5.657-5.657M27.875 12.5v-8m4.596 9.904l5.657-5.657M34.375 19h8m-9.904 4.596l5.657 5.657");
}

.v03br_b0w {
  cx: 6.375px;
  cy: 19px;
  r: 0.75px;
  fill: currentColor;
}

.zgfh01w5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.875 33.5a14.5 14.5 0 1 1 14.5-14.5a14.517 14.517 0 0 1-14.5 14.5m0-21a6.5 6.5 0 1 0 6.5 6.5a6.51 6.51 0 0 0-6.5-6.5");
}

</style>
