<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pffzxibed"/><path class="ayv2sibdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:digital-slate" /></template>
<style>
.ayv2sibdc {
  d: path("M8.75 13h6.5A1.75 1.75 0 0 1 17 14.75V16a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 16v-1.25A1.75 1.75 0 0 1 8.75 13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pffzxibed {
  d: path("m4.178 3.86l14.918-1.568a1.5 1.5 0 0 1 1.649 1.335a1.5 1.5 0 0 1-1.335 1.648L4.492 6.843a1.5 1.5 0 0 1-1.649-1.335A1.5 1.5 0 0 1 4.178 3.86M6.5 9.75h11a3.5 3.5 0 0 1 3.5 3.5v4.25a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5v-4.25a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
