<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ebvczzbhc"/><path class="vwibguupl"/><path class="qjhi8_b0z"/><path class="sxlwlmkmh"/><path class="hzsvawc8s"/><path class="u8aszkb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-left-right-duotone-bold" /></template>
<style>
.ebvczzbhc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hzsvawc8s {
  d: path("m8 8 -4 4 4 4");
}

.qjhi8_b0z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

.u8aszkb6i {
  d: path("m16 8 4 4 -4 4");
}

.vwibguupl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
