<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fvt2-0orr"/><path class="u4sowhi7h"/><path class="xslfg2evh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cold-snap-outline-bold" /></template>
<style>
.fvt2-0orr {
  d: path("M12 4v8m-4 0 8 -8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u4sowhi7h {
  d: path("M4 16h16");
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
