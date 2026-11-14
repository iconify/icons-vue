<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq0n_bb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-count-two" /></template>
<style>
.vq0n_bb_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 12l-.75-7a1.75 1.75 0 0 1 3.5-.25l1 5.25l1.25-6a1.75 1.75 0 0 1 3.25.5l-.75 6q4.5-1 5 2V15c0 4-2.5 6.5-6 6.5c-4 0-6.5-2.5-6.5-6.5Zm4 2.5H15");
}

</style>
