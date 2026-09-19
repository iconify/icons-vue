<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qv2xtygpq"/><path class="tfv0blbio"/><path class="oto5mz67w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anymemo" /></template>
<style>
.oto5mz67w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.8 36.4l2.6 4.5h10.1l-8.4-14.6h-8.4l-1.6 2.5h-2.2l-1.6-2.5h-8.4L4.5 40.9h10.1l2.6-4.5l2.5 4.5h8.6z");
}

.qv2xtygpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.1 26.3L24 7.1L12.9 26.3");
}

.tfv0blbio {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.3 26.3v-3.5l1.6-2.4h2.2l1.6 2.4v3.5");
}

</style>
