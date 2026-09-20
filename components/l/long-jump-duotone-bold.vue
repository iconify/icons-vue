<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qecovn3xi"/><path class="no0krsbuo"/><path class="kn0tcm93r"/><path class="gdee6mpzo"/><path class="z6mlq-bwt"/><path class="o46_3ibvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:long-jump-duotone-bold" /></template>
<style>
.gdee6mpzo {
  d: path("M8 7c4 0 7 4 7 8");
}

.kn0tcm93r {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.no0krsbuo {
  fill: currentColor;
  d: path("M11 16h10v4H11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o46_3ibvz {
  d: path("M3 20h6");
}

.qecovn3xi {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z6mlq-bwt {
  d: path("M11 16h10v4H11Z");
}

</style>
