<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kw-3gqg7o"/><circle class="hpw3u8bic"/><path class="i6m865g4k"/><circle class="cvjbgb8-y"/><path class="k5joeb94c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lightplan" /></template>
<style>
.cvjbgb8-y {
  cx: 24px;
  cy: 30.61px;
  r: 12.89px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hpw3u8bic {
  cx: 24.19px;
  cy: 11.26px;
  r: 3.38px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i6m865g4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.19 5.75a3.06 3.06 0 0 0-2.75-1.25h-.25a3.36 3.36 0 0 0-3.38 3.38v3.38m-5.09 3.38a2.51 2.51 0 0 0 2.52-2.51h0a2.51 2.51 0 0 0-2.52-2.51h0a2.52 2.52 0 0 0 2.52-2.51h0a2.52 2.52 0 0 0-2.52-2.52m-4.14 9.21a4.27 4.27 0 0 0 3.12.84h1m-4.12-9.21a4.27 4.27 0 0 1 3.12-.84h1");
}

.k5joeb94c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 22.19v8.42l6.64 4.36");
}

.kw-3gqg7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.17 13.76a4 4 0 0 0 3 .88h.38a3.35 3.35 0 0 0 3.29-3.29h0a3.35 3.35 0 0 0-3.29-3.3h-3.38V4.5h6.72");
}

</style>
