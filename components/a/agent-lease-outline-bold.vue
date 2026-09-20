<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vdkmp2b9k"/><path class="u5q3xebkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-lease-outline-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u5q3xebkh {
  d: path("M9 14h6l-6 6h6Z");
}

.vdkmp2b9k {
  d: path("M13.9 2.42a4.5 4.5 0 1 1 -3.8 0");
}

</style>
