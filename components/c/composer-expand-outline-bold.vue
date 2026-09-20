<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="om4dt2bov"/><path class="m51ptibtg"/><path class="tdul-wdwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:composer-expand-outline-bold" /></template>
<style>
.m51ptibtg {
  d: path("M6 11.5v4");
}

.om4dt2bov {
  d: path("M2 11a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tdul-wdwn {
  d: path("m9 6 3 -3 3 3");
}

</style>
