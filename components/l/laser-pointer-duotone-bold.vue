<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jifmu5b_n"/><path class="c__qe1vzx"/><path class="r_2fvubda"/><path class="qh7t7707e"/><path class="p2apttb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:laser-pointer-duotone-bold" /></template>
<style>
.c__qe1vzx {
  fill: currentColor;
  d: path("M17.5 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jifmu5b_n {
  fill: currentColor;
  d: path("M2 19a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p2apttb3i {
  d: path("M17.5 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qh7t7707e {
  d: path("m9 16.5 7 -7");
}

.r_2fvubda {
  d: path("M2 19a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
