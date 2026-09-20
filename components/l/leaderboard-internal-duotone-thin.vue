<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p4s9ffb9k"/><path class="kavs8h2ql"/><path class="h0jlkkbwp"/><path class="pg64rfbtc"/><path class="g7go0l5ag"/><path class="wew0vnk_n"/><path class="j6riv-b4h"/><path class="w0e70wbbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leaderboard-internal-duotone-thin" /></template>
<style>
.g7go0l5ag {
  d: path("M5 11v8");
}

.h0jlkkbwp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 14v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6riv-b4h {
  d: path("M19 14v5");
}

.kavs8h2ql {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p4s9ffb9k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pg64rfbtc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w0e70wbbt {
  d: path("M3 21.5h18");
}

.wew0vnk_n {
  d: path("M12 5v14");
}

</style>
