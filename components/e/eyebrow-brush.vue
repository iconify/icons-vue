<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t76rltbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eyebrow-brush" /></template>
<style>
.t76rltbgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.47 12.78za1.5 1.5 0 0 1 0 2.122l-4.243 4.242a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l4.242-4.243a1.5 1.5 0 0 1 2.122 0m7.424-7.424L11.47 12.78m5.303-8.131l2.828 2.828m-5.303-1.061l3.536 3.536m-5.657-1.414l3.535 3.535");
}

</style>
