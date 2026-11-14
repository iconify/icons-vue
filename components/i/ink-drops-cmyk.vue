<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lymv6swgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ink-drops-cmyk" /></template>
<style>
.lymv6swgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3s-3 3-3 4.5a3 3 0 0 0 6 0c0-1.5-3-4.5-3-4.5m9 0s-3 3-3 4.5a3 3 0 0 0 6 0c0-1.5-3-4.5-3-4.5m-9 10.5s-3 3-3 4.5a3 3 0 0 0 6 0c0-1.5-3-4.5-3-4.5m9 0s-3 3-3 4.5a3 3 0 0 0 6 0c0-1.5-3-4.5-3-4.5");
}

</style>
