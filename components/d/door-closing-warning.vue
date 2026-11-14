<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1a6wabnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:door-closing-warning" /></template>
<style>
.l1a6wabnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 9.75h1.25a2.625 2.625 0 0 1 2.625 2.625v6.5A2.625 2.625 0 0 1 7.875 21.5h-1.25A2.625 2.625 0 0 1 4 18.875v-6.5A2.625 2.625 0 0 1 6.625 9.75m9.5 0h1.25A2.625 2.625 0 0 1 20 12.375v6.5a2.625 2.625 0 0 1-2.625 2.625h-1.25a2.625 2.625 0 0 1-2.625-2.625v-6.5a2.625 2.625 0 0 1 2.625-2.625M9.5 7a3.5 3.5 0 0 1 5 0M8 4.5a6.5 6.5 0 0 1 8 0");
}

</style>
