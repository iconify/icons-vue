<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pic0zyzsz"/><path class="bpraj44ru"/><path class="t2pecxbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chat-requests-inbox" /></template>
<style>
.bpraj44ru {
  d: path("M2.5 20L6 13h15.5l-3 7Zm5-7V9.5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1V13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pic0zyzsz {
  d: path("M2.5 20V5A1.5 1.5 0 0 1 4 3.5h4.5l2 2H18A1.5 1.5 0 0 1 19.5 7v6");
}

.t2pecxbrd {
  d: path("M7.75 8.75L12 10.5l4.25-1.75");
}

</style>
