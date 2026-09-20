<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zajsl6b4z"/><path class="u6i63ebjk"/><path class="bc38ssbmv"/><path class="r7xk8o29f"/><path class="nxg78fr6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flip-h-duotone-bold" /></template>
<style>
.bc38ssbmv {
  d: path("m3 6 6 6 -6 6Z");
}

.nxg78fr6n {
  d: path("m21 6 -6 6 6 6Z");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u6i63ebjk {
  fill: currentColor;
  d: path("m21 6 -6 6 6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zajsl6b4z {
  fill: currentColor;
  d: path("m3 6 6 6 -6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
