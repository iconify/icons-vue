<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jqwxvo9pv"/><path class="g6zy60b7u"/><path class="z5x3c_05g"/><path class="tcbtlrbob"/><path class="i1wcr27il"/><path class="ow28lfbqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:biometric-duotone-bold" /></template>
<style>
.g6zy60b7u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 17a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i1wcr27il {
  d: path("M5 17a7 7 0 0 1 14 0");
}

.jqwxvo9pv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 17a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ow28lfbqg {
  d: path("M2 17a10 10 0 0 1 20 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tcbtlrbob {
  d: path("M8 17a4 4 0 0 1 8 0");
}

.z5x3c_05g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 17a10 10 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
