<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bl6348g8x"/><rect class="a6e6h5bml"/><path class="mj-0syf0t"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drom" /></template>
<style>
.a6e6h5bml {
  width: 4.124px;
  height: 5.465px;
  x: 26.12px;
  y: 14.307px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.062px;
  ry: 2.062px;
}

.bl6348g8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.717 21.88v-2.114H10.5v2.114m6.083-2.114v-7.784h-3.918c0 3.17-.233 5.252-1.134 7.784m20.814 0v-5.459l2.577 5.465l2.578-5.456v5.456");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.mj-0syf0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.857 17.71c0 1.139.923 2.062 2.062 2.062h0a2.06 2.06 0 0 0 2.062-2.062v-1.34a2.06 2.06 0 0 0-2.062-2.062h0a2.06 2.06 0 0 0-2.062 2.062m0-2.063v8.249m6.875 13.462v-2.113h-7.217v2.113m6.083-2.113V26.12H21.68c0 3.171-.233 5.253-1.134 7.785m15.775 2.113v-2.113h-7.217v2.113m6.083-2.113V26.12h-3.918c0 3.171-.234 5.253-1.135 7.785m-18.455.464V26.12h5.465v8.249");
}

</style>
