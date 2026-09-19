<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="kh48f7uho"/><circle class="cpk0fnbgt"/><path class="e0dhc2lwe"/><path class="garsomv5t"/><path class="xiye5yiaa"/><path class="qrlir5brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:giga-text" /></template>
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

.e0dhc2lwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.147 29.252s4.322-3.134 8.458-3.134v-13.29a6.07 6.07 0 0 1 6.07-6.07h0c1.35 0 2.66.468 3.704 1.324l6.239 5.115a3.15 3.15 0 0 1 .993 3.43h0a3.15 3.15 0 0 1-2.991 2.16h-4.385v10.646");
}

.garsomv5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.583 36.608c4.862-6.248 10.419-7.182 13.39-7.182c2.412 0 5.047-.057 5.047 2.019c0 2.608-3.168 2.503-4.682 2.503c-1.037 7.002-4.455 9.967-4.455 9.967");
}

.kh48f7uho {
  cx: 17.766px;
  cy: 11.875px;
  r: 1.409px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qrlir5brh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.375 28.82a1.841 1.841 0 0 0-3.418-.948a1.841 1.841 0 0 0-3.294 1.607c.61 1.752 3.294 3.673 3.294 3.673s2.685-1.922 3.294-3.673c.079-.205.124-.426.124-.659");
}

.xiye5yiaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.11 33.71a3.13 3.13 0 0 0 3.04 2.42h9.62c1.72 0 3.11-1.4 3.11-3.12v-5.89c0-1.72-1.39-3.12-3.11-3.12h-9.62c-1.72 0-3.12 1.4-3.12 3.12v2.47");
}

</style>
