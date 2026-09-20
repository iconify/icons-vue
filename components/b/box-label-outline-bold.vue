<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nib87abyv"/><path class="a7vpafiwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:box-label-outline-bold" /></template>
<style>
.a7vpafiwa {
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nib87abyv {
  d: path("M4 8h12l4 4 -4 4H4Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
