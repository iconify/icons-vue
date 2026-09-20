<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="obcmadc5g"/><path class="okiuenbyh"/><path class="l0v-b4kbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:doormat-duotone-bold" /></template>
<style>
.l0v-b4kbr {
  d: path("M8 12h8");
}

.obcmadc5g {
  fill: currentColor;
  d: path("m3 16 7 -7h4l7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.okiuenbyh {
  d: path("m3 16 7 -7h4l7 7Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
