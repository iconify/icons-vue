<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqlvtpa7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:batch-production" /></template>
<style>
.lqlvtpa7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.375 3h3.25a2.625 2.625 0 0 1 2.625 2.625v1.5a2.625 2.625 0 0 1-2.625 2.625h-3.25A2.625 2.625 0 0 1 7.75 7.125v-1.5A2.625 2.625 0 0 1 10.375 3m-5.25 9.5h2.75a2.625 2.625 0 0 1 2.625 2.625v3.25A2.625 2.625 0 0 1 7.875 21h-2.75A2.625 2.625 0 0 1 2.5 18.375v-3.25A2.625 2.625 0 0 1 5.125 12.5m11 0h2.75a2.625 2.625 0 0 1 2.625 2.625v3.25A2.625 2.625 0 0 1 18.875 21h-2.75a2.625 2.625 0 0 1-2.625-2.625v-3.25a2.625 2.625 0 0 1 2.625-2.625M12 3v3m-5.5 6.5v3m11-3v3");
}

</style>
