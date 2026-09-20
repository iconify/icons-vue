<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t2xnbczjm"/><path class="lkivjibuo"/><path class="p6px4qbbr"/><path class="pmv9af26x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:broccoli-outline-bold" /></template>
<style>
.lkivjibuo {
  d: path("M12 13v7");
}

.p6px4qbbr {
  d: path("M12 16H8");
}

.pmv9af26x {
  d: path("M12 16h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t2xnbczjm {
  d: path("M5 13a4 4 0 0 1 4 -6 4 4 0 0 1 6 0 4 4 0 0 1 4 6Z");
}

</style>
