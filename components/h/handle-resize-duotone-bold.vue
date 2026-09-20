<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yvhspgbdy"/><path class="if8unzboi"/><path class="dqy0akhac"/><path class="zuxjsnblj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handle-resize-duotone-bold" /></template>
<style>
.dqy0akhac {
  d: path("m16 16 4.5 4.5");
}

.if8unzboi {
  d: path("M3 5a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yvhspgbdy {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zuxjsnblj {
  d: path("M16.5 20.5h4v-4");
}

</style>
