<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sdgafkcgw"/><path class="lgr612izs"/><path class="aagj9lb5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:goal-met-outline-bold" /></template>
<style>
.aagj9lb5p {
  d: path("m17 13 2 2 3 -3");
}

.lgr612izs {
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sdgafkcgw {
  d: path("M4 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
