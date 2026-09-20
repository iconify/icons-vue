<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxjvqtiry"/><path class="xz0177cqa"/><path class="qe97cg-lx"/><path class="qj99nibfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grokking-duotone-bold" /></template>
<style>
.qe97cg-lx {
  d: path("M3 3v18h18");
}

.qj99nibfx {
  d: path("M6 18h8l4 -4V6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xz0177cqa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 18h8l4 -4V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yxjvqtiry {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
