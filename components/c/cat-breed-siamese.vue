<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jjj7wfbku"/><path class="yhdeqxbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cat-breed-siamese" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jjj7wfbku {
  d: path("m4 3l5 3.5h6L20 3v8c0 5.5-3.5 10-8 10s-8-4.5-8-10Z");
}

.yhdeqxbav {
  d: path("M11.753 13.75h.494a1.206 1.206 0 0 1 1.003 1.875a1.502 1.502 0 0 1-2.5 0a1.206 1.206 0 0 1 1.003-1.875M8.5 11h.01m6.99 0h.01");
}

</style>
