<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ur2t430wi"/><path class="xqw8iyb8j"/><path class="k39_q7ldr"/><path class="tcbtlrbob"/><path class="i1wcr27il"/><path class="ow28lfbqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:biometric-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1wcr27il {
  d: path("M5 17a7 7 0 0 1 14 0");
}

.k39_q7ldr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 17a10 10 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ow28lfbqg {
  d: path("M2 17a10 10 0 0 1 20 0");
}

.tcbtlrbob {
  d: path("M8 17a4 4 0 0 1 8 0");
}

.ur2t430wi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 17a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xqw8iyb8j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 17a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
