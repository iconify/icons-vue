<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="yae139ebf"/><path class="xe-ykv5gv"/><path class="wf_-m8btb"/><path class="dr5339brd"/><path class="zwohoxmzp"/><circle class="m-jcpyvdb"/><circle class="fo8jg1xtf"/><path class="nt-90xbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:leclercdrive" /></template>
<style>
.dr5339brd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.032 16.897a6.116 6.116 0 0 0-8.12-7.704m23.892 25.021H26.4a1.326 1.326 0 0 1-1.326-1.326v-4.55c0-.733.593-1.326 1.326-1.326h13.684");
}

.fo8jg1xtf {
  cx: 37.432px;
  cy: 41.037px;
  r: 1.599px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m-jcpyvdb {
  cx: 28.894px;
  cy: 41.037px;
  r: 1.599px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nt-90xbhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.925 11.889v9.358m-1.599-9.358h3.197m-3.197 9.358h3.197c1.43 0 2.593-.34 3.245-1.604h1.023");
}

.wf_-m8btb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.96 19.971a10.6 10.6 0 0 0 .783-4.005c0-5.854-4.746-10.6-10.6-10.6s-10.601 4.746-10.601 10.6c0 4.851 3.259 8.941 7.707 10.2");
}

.xe-ykv5gv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.01 34.235a6.078 6.078 0 0 0-10.937 4.435v-.001c-2.197.01-3.655-.35-4.497-.656a2.44 2.44 0 0 1-1.352-1.21c-2.207-4.45.804-8.92 7.018-10.614c2.767-4.352 14.795-10.71 24.578-1.494");
}

.yae139ebf {
  cx: 18.091px;
  cy: 37.805px;
  r: 3.957px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zwohoxmzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.72 36.561h12.694l1.935-11.066h2.047");
}

</style>
