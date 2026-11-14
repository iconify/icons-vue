<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dl3_mccoq"/><path class="ssh8mqvlp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:enter-tunnel" /></template>
<style>
.dl3_mccoq {
  d: path("M2.5 21.5V12a9.5 9.5 0 0 1 19 0v9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ssh8mqvlp {
  d: path("M6.5 19.5v-4l2-4h7l2 4v4Zm0-4h11");
}

</style>
