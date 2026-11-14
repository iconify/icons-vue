<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_29g8b8l"/><path class="cy2pyp3_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inhaler" /></template>
<style>
.cy2pyp3_u {
  d: path("M12.375 2.5h.75a2.625 2.625 0 0 1 2.625 2.625v4.75a2.625 2.625 0 0 1-2.625 2.625h-.75A2.625 2.625 0 0 1 9.75 9.875v-4.75A2.625 2.625 0 0 1 12.375 2.5M9.75 5h6m-11 12v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s_29g8b8l {
  d: path("M9 9v5.5H4.5c-1.1 0-2 .9-2 2v3c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V9");
}

</style>
