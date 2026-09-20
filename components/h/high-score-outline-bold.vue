<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eq8p65fcb"/><path class="r182r524c"/><path class="zf9agzw6m"/><path class="s7u5an2xj"/><path class="pf3d8ibrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:high-score-outline-bold" /></template>
<style>
.eq8p65fcb {
  d: path("M4 4v16h16V4Z");
}

.pf3d8ibrz {
  d: path("m15 7 2 -2 2 2");
}

.r182r524c {
  d: path("M7 9h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s7u5an2xj {
  d: path("M7 17h8");
}

.zf9agzw6m {
  d: path("M7 13h7");
}

</style>
