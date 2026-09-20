<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="vzl8cib_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-data-outline-bold" /></template>
<style>
.moha5wbmp {
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vzl8cib_u {
  d: path("M9 12a1.5 1.5 0 0 1 3 0 1.5 1.5 0 0 1 3 0l-3 3Z");
}

.yix-58bnj {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
