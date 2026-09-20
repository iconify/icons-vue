<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y9vlkac4c"/><path class="ukg9klbsl"/><path class="ezj_gmbcp"/><path class="mgny0cq-k"/><path class="k0kvi05dj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:filtered-chat-duotone-bold" /></template>
<style>
.ezj_gmbcp {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.k0kvi05dj {
  d: path("M7.5 6h9l-3 3v5h-3V9Z");
}

.mgny0cq-k {
  d: path("M6 18v3l3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ukg9klbsl {
  fill: currentColor;
  d: path("M7.5 6h9l-3 3v5h-3V9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y9vlkac4c {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
