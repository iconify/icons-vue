<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aum8yac4r"/><path class="xx-zvzb7h"/><path class="tgd916uxo"/><path class="ebby1xbgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:draft-model-duotone-bold" /></template>
<style>
.aum8yac4r {
  fill: currentColor;
  d: path("M5 9.5 7.5 12 5 14.5 2.5 12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ebby1xbgn {
  d: path("M16.5 6.5 22 12l-5.5 5.5L11 12Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tgd916uxo {
  d: path("M5 9.5 7.5 12 5 14.5 2.5 12Z");
}

.xx-zvzb7h {
  fill: currentColor;
  d: path("M16.5 6.5 22 12l-5.5 5.5L11 12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
