<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="le41ikb_c"/><path class="pemn838wn"/><path class="a78gppbhl"/><path class="ixxrscbjj"/><path class="fxla4ib-b"/><path class="tpi3f12bz"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:desert-duotone-thin" /></template>
<style>
.a78gppbhl {
  d: path("M6 6h2.5");
}

.fxla4ib-b {
  d: path("M2 19a6 6 0 0 1 12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixxrscbjj {
  d: path("M15.5 6H18");
}

.le41ikb_c {
  fill: currentColor;
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pemn838wn {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.tpi3f12bz {
  d: path("M12 19a5 5 0 0 1 10 0");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
