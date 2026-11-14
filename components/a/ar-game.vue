<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f5ss92bwz"/><path class="s0wlx0b_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ar-game" /></template>
<style>
.f5ss92bwz {
  d: path("M6.5 11.5h11c2.5 0 4 2 4 5s-2.5 4-4.5 2L15.5 17h-7L7 18.5c-2 2-4.5 1-4.5-2s1.5-5 4-5m-1 3.25h3M7 13.25v3m10-1.5h.01M12.671 2.835l1.5.75A1.5 1.5 0 0 1 15 4.927v1.146a1.5 1.5 0 0 1-.829 1.342l-1.5.75a1.5 1.5 0 0 1-1.342 0l-1.5-.75A1.5 1.5 0 0 1 9 6.073V4.927a1.5 1.5 0 0 1 .829-1.342l1.5-.75a1.5 1.5 0 0 1 1.342 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s0wlx0b_c {
  d: path("m9 4l3 1.5L15 4m-3 1.5v3");
}

</style>
