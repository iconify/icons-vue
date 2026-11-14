<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s6af0sa3w"/><path class="tjuz155bh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cute-dog" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s6af0sa3w {
  d: path("M6 10.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

.tjuz155bh {
  d: path("M7.5 6.5c-3-1.5-5 1-4.5 5.5c.25 2 2.25 2 3.25.25M16.5 6.5c3-1.5 5 1 4.5 5.5c-.25 2-2.25 2-3.25.25m-7.5 6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M9.75 10h.01m4.49 0h.01M12 13h.01");
}

</style>
