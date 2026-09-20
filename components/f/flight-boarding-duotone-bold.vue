<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v7p687byl"/><path class="m44w6yf_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flight-boarding-duotone-bold" /></template>
<style>
.m44w6yf_n {
  d: path("m12 2 2.5 2.5v5L21 16h-6.5v3l2.5 2.5H7L9.5 19v-3H3l6.5 -6.5v-5Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v7p687byl {
  fill: currentColor;
  d: path("m12 2 2.5 2.5v5L21 16h-6.5v3l2.5 2.5H7L9.5 19v-3H3l6.5 -6.5v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
