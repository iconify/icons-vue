<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h2-2dgnfu"/><path class="tdul-wdwn"/><path class="vy337188j"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:height-measure-outline-bold" /></template>
<style>
.h2-2dgnfu {
  d: path("M12 3v18");
}

.rjrs_5bsc {
  d: path("M6 3h12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tdul-wdwn {
  d: path("m9 6 3 -3 3 3");
}

.vy337188j {
  d: path("m9 18 3 3 3 -3");
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
