<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x8ow89bbk"/><path class="woa15cb-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jump-starter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.woa15cb-r {
  d: path("m8.717 11.559l-1.788 2.264A.727.727 0 0 0 7.5 15a1.08 1.08 0 0 1 1.026 1.423L8.5 16.5a.325.325 0 0 0 .55.318l1.953-2.197A.674.674 0 0 0 10.5 13.5a1.193 1.193 0 0 1-1.163-1.462l.038-.163a.374.374 0 0 0-.658-.316");
}

.x8ow89bbk {
  d: path("M6 7.5h6a3.5 3.5 0 0 1 3.5 3.5v6a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17v-6A3.5 3.5 0 0 1 6 7.5m-1.25 0V5h2.5v2.5m3.5 0V5h2.5v2.5M15.5 11H18a2 2 0 0 1 2 2v3.5m-1.75 0h3.5L21 21h-2Z");
}

</style>
