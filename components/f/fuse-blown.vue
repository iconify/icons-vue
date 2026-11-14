<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qfnjfgt7e"/><path class="wkssh-j0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fuse-blown" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qfnjfgt7e {
  d: path("M8.5 7.5h7A1.5 1.5 0 0 1 17 9v6a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 15V9a1.5 1.5 0 0 1 1.5-1.5M4.25 7h1A1.75 1.75 0 0 1 7 8.75v6.5A1.75 1.75 0 0 1 5.25 17h-1a1.75 1.75 0 0 1-1.75-1.75v-6.5A1.75 1.75 0 0 1 4.25 7m14.5 0h1a1.75 1.75 0 0 1 1.75 1.75v6.5A1.75 1.75 0 0 1 19.75 17h-1A1.75 1.75 0 0 1 17 15.25v-6.5A1.75 1.75 0 0 1 18.75 7");
}

.wkssh-j0u {
  d: path("m7 12l1.75-1.5l1.75 3m3-3l1.75 3L17 12");
}

</style>
