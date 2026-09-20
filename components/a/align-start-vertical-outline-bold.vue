<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="crv4i00bu"/><path class="q7xe92bpy"/><path class="w329m1boj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-start-vertical-outline-bold" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.q7xe92bpy {
  d: path("M7 7h10v4H7Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w329m1boj {
  d: path("M7 14h6v4H7Z");
}

</style>
