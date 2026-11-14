<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyk846jdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:funnel-split" /></template>
<style>
.wyk846jdq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.527 3.5h8.946a1.75 1.75 0 0 1 1.279 2.944l-3.733 4A1.75 1.75 0 0 1 12.74 11h-1.48a1.75 1.75 0 0 1-1.279-.556l-3.733-4A1.75 1.75 0 0 1 7.527 3.5m2.973 11l-5 5m0-4v4h4m4-5l5 5m-4 0h4v-4");
}

</style>
