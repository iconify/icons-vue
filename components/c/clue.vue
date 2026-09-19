<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="j_1-wshre"/><path class="cg5z_ybjg"/><path class="wzqa-ryau"/><path class="sop2lkbsv"/><path class="v53214ucn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clue" /></template>
<style>
.cg5z_ybjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.3 18.6c-2.7-.2-5.3.6-7.4 2c.3-2.5-.4-5.1-1.9-7.4c-1.5 2.3-2.2 4.9-1.9 7.4c-2-1.5-4.7-2.2-7.4-2h0c1.2 2.4 3.1 4.3 5.4 5.4c-2.3 1-4.2 2.9-5.4 5.4c2.7.2 5.3-.6 7.4-2c-.3 2.5.4 5.1 1.9 7.4c1.5-2.3 2.2-4.9 1.9-7.4c2 1.5 4.7 2.2 7.4 2h0c-1.2-2.4-3.1-4.3-5.4-5.4c2.3-1 4.2-2.9 5.4-5.4");
}

.j_1-wshre {
  cx: 24px;
  cy: 24px;
  r: 10.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sop2lkbsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 34.7c-.9 1.6-2.2 3-3.9 3.9c-5.1 3-11.7 1.2-14.7-3.9S4.2 23 9.3 20.1c1.7-1 3.6-1.4 5.4-1.4m0-.1c-.9-1.6-1.4-3.4-1.4-5.4c0-5.9 4.8-10.7 10.7-10.7s10.7 4.8 10.7 10.7c0 2-.5 3.8-1.4 5.4");
}

.v53214ucn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.3 29.4c.9 1.6 1.4 3.4 1.4 5.4c0 5.9-4.8 10.7-10.7 10.7s-10.7-4.8-10.7-10.7c0-2 .5-3.8 1.4-5.4M24 13.3c.9-1.6 2.2-3 3.9-3.9c5.1-3 11.7-1.2 14.7 3.9S43.8 25 38.7 28c-1.7 1-3.5 1.4-5.4 1.4m-18.6 0c-1.8 0-3.7-.5-5.4-1.4c-5.1-3-6.9-9.5-3.9-14.7s9.5-6.9 14.7-3.9c1.7 1 3 2.4 3.9 3.9");
}

.wzqa-ryau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.3 18.6c1.8 0 3.7.5 5.4 1.4c5.1 3 6.9 9.5 3.9 14.7c-3 5.1-9.5 6.9-14.7 3.9c-1.7-1-3-2.4-3.9-3.9");
}

</style>
