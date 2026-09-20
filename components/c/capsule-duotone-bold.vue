<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h1q7nzbdi"/><path class="u-mqtjbzo"/><path class="l0v-b4kbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:capsule-duotone-bold" /></template>
<style>
.h1q7nzbdi {
  fill: currentColor;
  d: path("M8 7a4 4 0 0 1 8 0v10a4 4 0 0 1 -8 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u-mqtjbzo {
  d: path("M8 7a4 4 0 0 1 8 0v10a4 4 0 0 1 -8 0Z");
}

</style>
