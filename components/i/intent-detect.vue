<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrhl45kif"/><path class="omquiubnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:intent-detect" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.omquiubnj {
  d: path("M8 10.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4 0h.01");
}

.zrhl45kif {
  d: path("M6 3.5h12A2.5 2.5 0 0 1 20.5 6v9a2.5 2.5 0 0 1-2.5 2.5h-8L6 21v-3.5A2.5 2.5 0 0 1 3.5 15V6A2.5 2.5 0 0 1 6 3.5");
}

</style>
