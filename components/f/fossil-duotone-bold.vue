<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qiiqlubje"/><path class="mb4ot6b9u"/><path class="ptnaezjlv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fossil-duotone-bold" /></template>
<style>
.mb4ot6b9u {
  d: path("M4 11c0 -4 4 -7 8 -7 5 0 8 4 8 8 0 5 -4 8 -8 8 -5 0 -8 -4 -8 -9");
}

.ptnaezjlv {
  d: path("M12 8c2 0 4 2 4 4 0 3 -3 5 -5 4s-2 -4 0 -5c1.5 -0.5 3 0 3 1.5");
}

.qiiqlubje {
  fill: currentColor;
  d: path("M4 11c0 -4 4 -7 8 -7 5 0 8 4 8 8 0 5 -4 8 -8 8 -5 0 -8 -4 -8 -9");
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

</style>
