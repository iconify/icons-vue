<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z720dd3bk"/><path class="g_bnyexhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-mic" /></template>
<style>
.g_bnyexhm {
  d: path("M4 13a5 5 0 0 0 10 0m-5 5v3m9.125-16.375l.139.324a1.5 1.5 0 0 0 .787.787l.324.139a.408.408 0 0 1 0 .75l-.324.139a1.5 1.5 0 0 0-.787.787l-.139.324a.408.408 0 0 1-.75 0l-.139-.324a1.5 1.5 0 0 0-.787-.787l-.324-.139a.408.408 0 0 1 0-.75l.324-.139a1.5 1.5 0 0 0 .787-.787l.139-.324a.408.408 0 0 1 .75 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z720dd3bk {
  d: path("M9 7.5za2.5 2.5 0 0 1 2.5 2.5v4A2.5 2.5 0 0 1 9 16.5A2.5 2.5 0 0 1 6.5 14v-4A2.5 2.5 0 0 1 9 7.5");
}

</style>
