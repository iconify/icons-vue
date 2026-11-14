<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mglym2bvm"/><path class="uymvbvt2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:karaoke-mic-play" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mglym2bvm {
  d: path("M8.5 8a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.uymvbvt2u {
  d: path("m10.237 11.737l.026.026a1.75 1.75 0 0 1 0 2.474l-4.026 4.026a1.75 1.75 0 0 1-2.474 0l-.026-.026a1.75 1.75 0 0 1 0-2.474l4.026-4.026a1.75 1.75 0 0 1 2.474 0m7.519 4.579l1.523.888a1.5 1.5 0 0 1 0 2.592l-1.523.888a1.5 1.5 0 0 1-2.256-1.296v-1.776a1.5 1.5 0 0 1 2.256-1.296");
}

</style>
