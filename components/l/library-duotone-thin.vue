<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="odu85s2ca"/><path class="lzc28-gln"/><path class="yzcdzmlnf"/><path class="t6wf8ob_n"/><path class="woetzacvo"/><path class="dznv025mt"/><path class="taxmbub4q"/><path class="u78lc2bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:library-duotone-thin" /></template>
<style>
.dznv025mt {
  d: path("M6 14h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lzc28-gln {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.odu85s2ca {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 12 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t6wf8ob_n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 20h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.taxmbub4q {
  d: path("M6 17h12");
}

.u78lc2bnx {
  d: path("M6 20h12");
}

.woetzacvo {
  d: path("m4 12 8 -8 8 8");
}

.yzcdzmlnf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
