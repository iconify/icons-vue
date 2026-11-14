<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kfs834xzy"/><path class="jnzihrbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:assistive-listening" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnzihrbis {
  d: path("M12.25 9a2.75 2.75 0 0 1 5.5 0c0 1.25-1 1.75-2 2.5m-9.915 2.75a2.5 2.5 0 0 1 0-2.5m-1.931 4.118a5 5 0 0 1 0-5.736");
}

.kfs834xzy {
  d: path("M9.5 9a5.5 5.5 0 0 1 11 0c0 3-2.25 4.25-3 6.25c-.6 1.75-1.75 4.25-4.25 4.25c-1.75 0-3-1-3.5-2.25");
}

</style>
