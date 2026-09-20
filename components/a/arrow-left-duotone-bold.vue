<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ebvczzbhc"/><path class="facqd0bly"/><path class="sxlwlmkmh"/><path class="s6jbysbtk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-left-duotone-bold" /></template>
<style>
.ebvczzbhc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.facqd0bly {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 7 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s6jbysbtk {
  d: path("m9 7 -5 5 5 5");
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

</style>
