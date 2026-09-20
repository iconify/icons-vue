<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uojx2-ana"/><path class="x_lkvk_2h"/><path class="ebuv7_btt"/><path class="x_s0a9b6h"/><path class="kpxqn84yq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chat-code-duotone-bold" /></template>
<style>
.ebuv7_btt {
  d: path("M7 17v3l3 -3");
}

.kpxqn84yq {
  d: path("M14.5 7 17 9.5 14.5 12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uojx2-ana {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x_lkvk_2h {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.x_s0a9b6h {
  d: path("M9.5 7 7 9.5 9.5 12");
}

</style>
