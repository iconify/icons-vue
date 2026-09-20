<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u-4a428mz"/><path class="g36u2t9sm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ipo-duotone-bold" /></template>
<style>
.g36u2t9sm {
  d: path("M9 15V8a3 3 0 0 1 6 0v7Zm0 -4 -3 3v3h3m6 -6 3 3v3h-3m-3 -2v5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u-4a428mz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 15V8a3 3 0 0 1 6 0v7Zm0 -4 -3 3v3h3m6 -6 3 3v3h-3m-3 -2v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
