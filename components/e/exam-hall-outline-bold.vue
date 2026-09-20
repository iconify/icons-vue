<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mupo5fbhr"/><path class="ehib3abci"/><path class="fhs8z1bjw"/><path class="fduloacov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:exam-hall-outline-bold" /></template>
<style>
.ehib3abci {
  d: path("M15 8h6v4h-6Z");
}

.fduloacov {
  d: path("M15 16h6v4h-6Z");
}

.fhs8z1bjw {
  d: path("M3 16h6v4H3Z");
}

.mupo5fbhr {
  d: path("M3 8h6v4H3Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
