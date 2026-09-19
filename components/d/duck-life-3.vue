<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hu5-43g9u"/><path class="m5m6s-dum"/><circle class="n91qdhs7z"/><path class="gccufr9kv"/><path class="dr4au5l2o"/><circle class="zc_j0mxce"/><path class="fad9iab3t"/><path class="v-tszbcms"/><circle class="r43bnbb_v"/><path class="jqs6o8bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:duck-life-3" /></template>
<style>
.dr4au5l2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.307 27.612l-1.376 1.595l-.364-2.226");
}

.fad9iab3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.226 22.88c-2.066-.617-3.457.146-3.702 2.193m29.966-9.988l-3.98 2.392c-1.149 2.432-2.632 3.57-5.202 4.045q-1.542.285-2.116 2.895l-4.003-5.637q-2.275-4.508.253-8.194c1.207-1.093 1.875-2.14 3.55-2.489l.925-1.85l1.209-.747");
}

.gccufr9kv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.506 29.108c-.43 2.055.315 3.285 2.322 3.357M5.53 10.612l6.1 3.677q4.042-.558 6.778 2.313q1.092 1.147 3.619.19l-2.558 6.504q-2.559 4.417-7.076 4.316q-2.388-.628-4.218-2.464l-2.664-.017m1.58-2.91c.036.013-1.482-.403-1.58-.436");
}

.hu5-43g9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.422 42.5c.18-2.176 1.008-3.82 2.278-5.308a6.662 6.662 0 1 1 11.293-.709c1.618 1.52 2.67 3.5 2.904 5.991");
}

.jqs6o8bti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.108 16.063c1-1.882.641-3.234-1.296-3.872m5.3-2.749l2.308-3.489q1.656-.909 3.156.333q1.692-1.05 2.873-.05q-1.578 5.681-5.413 8.386");
}

.m5m6s-dum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.352 30.957l2.3.817l-1.873 1.208");
}

.n91qdhs7z {
  cx: 27.949px;
  cy: 31.284px;
  r: 2.22px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r43bnbb_v {
  cx: 30.37px;
  cy: 13.822px;
  r: 2.256px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v-tszbcms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.074 11.171l-.953-2.691l2.424 1.034");
}

.zc_j0mxce {
  cx: 13.988px;
  cy: 23.324px;
  r: 2.281px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
