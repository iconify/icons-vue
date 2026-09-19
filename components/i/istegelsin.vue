<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="vz3lppbiz"/><circle class="ttq9pw1my"/><path class="vs46ocbvb"/><circle class="e2pk0eb0r"/><path class="wgu0niblu"/><circle class="okjqtgb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:istegelsin" /></template>
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

.e2pk0eb0r {
  cx: 30.799px;
  cy: 32.443px;
  r: 0.8px;
  fill: currentColor;
}

.okjqtgb8y {
  cx: 17.312px;
  cy: 7.324px;
  r: 0.8px;
  fill: currentColor;
}

.ttq9pw1my {
  cx: 30.015px;
  cy: 25.814px;
  r: 0.8px;
  fill: currentColor;
}

.vs46ocbvb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.799 34.266v4.104");
}

.vz3lppbiz {
  cx: 18.026px;
  cy: 22.301px;
  r: 0.8px;
  fill: currentColor;
}

.wgu0niblu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.021 18.736h8.132m2.404 3.565h-9.57m-3.544 3.513h9.408m-6.83 3.45h8.132m-11.869 5.002c0-1.14-.912-2.052-2.052-2.052s-2.052.912-2.052 2.052v2.052c0 1.14.912 1.976 2.052 1.976s2.052-.912 2.052-1.976h-2.052m16.525-21.127c-.228.456-.76.76-1.292.76c-.836 0-1.52-.684-1.52-1.52v-.988c0-.836.684-1.52 1.52-1.52s1.52.684 1.52 1.52v.532h-3.04m-8.231 1.672c.304.228.608.304 1.216.304h.304c.532 0 .988-.456.988-.988s-.456-.988-.988-.988h-.684c-.532 0-.988-.456-.988-.988s.456-.988.988-.988h.304c.684 0 .988.076 1.216.304m-1.025 25.231c-.228.456-.76.76-1.292.76c-.836 0-1.52-.684-1.52-1.52v-.988c0-.836.684-1.52 1.52-1.52s1.52.684 1.52 1.52v.532h-3.04m14.545 2.052v-4.104m3.04 4.104v-2.508c0-.836-.684-1.52-1.52-1.52s-1.52.684-1.52 1.52m-9.556-3.648v5.32c0 .456.304.76.76.76h.228m2.104-.304c.304.228.608.304 1.216.304h.304c.532 0 .988-.456.988-.988s-.456-.988-.988-.988h-.684c-.532 0-.988-.456-.988-.988s.456-.988.988-.988h.304c.684 0 .988.076 1.216.304m-4.496-22.723h1.672m-.836-1.216v4.56c0 .456.304.76.76.76h.228m-8.683-6.08v6.08");
}

</style>
