<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ype-dsbdp"/><path class="byl482lkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:integration-outline-bold" /></template>
<style>
.byl482lkm {
  d: path("M9.5 12a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ype-dsbdp {
  d: path("M3.5 12a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
}

</style>
