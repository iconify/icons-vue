<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s2r04acoo"/><path class="ahq5brb1v"/><path class="q518x4bkb"/><path class="gcalxb98a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:element-duotone-bold" /></template>
<style>
.ahq5brb1v {
  d: path("M5 4h14v14H5Z");
}

.gcalxb98a {
  d: path("M8 13h8");
}

.q518x4bkb {
  d: path("M5 9h14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s2r04acoo {
  fill: currentColor;
  d: path("M5 4h14v14H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
