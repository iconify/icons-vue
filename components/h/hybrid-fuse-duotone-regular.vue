<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x6g46mace"/><path class="dlyvfz7mq"/><path class="aeb4_busl"/><path class="e133p_f8o"/><path class="pr6npvbsh"/><path class="xxvssxb6x"/><path class="lqiw_3bos"/><path class="dhtq24lfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hybrid-fuse-duotone-regular" /></template>
<style>
.aeb4_busl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dhtq24lfs {
  d: path("m17 9.5 2.5 2.5 -2.5 2.5");
}

.dlyvfz7mq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 19 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e133p_f8o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 9.5 2.5 2.5 -2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lqiw_3bos {
  d: path("M10 12h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pr6npvbsh {
  d: path("m3 5 6 6");
}

.x6g46mace {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 5 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xxvssxb6x {
  d: path("m3 19 6 -6");
}

</style>
