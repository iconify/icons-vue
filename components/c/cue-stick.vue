<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qycaj-b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cue-stick" /></template>
<style>
.qycaj-b-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.432 14.568za1.75 1.75 0 0 1 0 2.475l-3.889 3.889a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475l3.889-3.889a1.75 1.75 0 0 1 2.475 0M9.5 14.5l11-11M5 16.5L7.5 19");
}

</style>
