<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lawno2fmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:houses" /></template>
<style>
.lawno2fmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 21h8m-8 0H3v-6.717a2 2 0 0 1 .683-1.506l3-2.625a2 2 0 0 1 2.634 0l3 2.625A2 2 0 0 1 13 14.283zm0-14h.01M17 7h.01M17 11h.01M17 15h.01M9 9.875V3h10a2 2 0 0 1 2 2v16");
}

</style>
