<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xw98gt_bk"/><path class="al_rqo_gu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lamp-smart-on" /></template>
<style>
.al_rqo_gu {
  d: path("M10.5 14v7M7 21h6.6M10.5 2v2.5M4 3.75L5.5 5M17 3.75L15.5 5m-1.25 12.75a5.5 5.5 0 0 1 7.5 0M16 19.5a2.75 2.75 0 0 1 4 0m-2 2h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xw98gt_bk {
  fill: currentColor;
  d: path("M7.41 7.5h6.18a1.75 1.75 0 0 1 1.612 1.068l1.269 3A1.75 1.75 0 0 1 14.859 14H6.141a1.75 1.75 0 0 1-1.612-2.432l1.269-3A1.75 1.75 0 0 1 7.41 7.5");
}

</style>
