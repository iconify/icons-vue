<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="unu7n2b0o"/><path class="nbts0_hxp"/><path class="pywr_yykw"/><path class="egda5-rke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:eco-label-duotone-bold" /></template>
<style>
.egda5-rke {
  d: path("M10.5 13.5c0 -4.2 2.8 -7 7 -7 0 4.2 -2.8 7 -7 7");
}

.nbts0_hxp {
  fill: currentColor;
  d: path("M10.5 13.5c0 -4.2 2.8 -7 7 -7 0 4.2 -2.8 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pywr_yykw {
  d: path("m4 12 8 -8h8v8l-8 8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.unu7n2b0o {
  fill: currentColor;
  d: path("m4 12 8 -8h8v8l-8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
