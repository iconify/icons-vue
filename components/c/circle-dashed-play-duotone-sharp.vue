<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lxr5h_bko"/><path class="cax6jrbtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-play-duotone-sharp" /></template>
<style>
.cax6jrbtl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.89 10.592a9 9 0 0 1 0 2.816m-1.61 3.882a9 9 0 0 1-1.99 1.991m-3.883 1.608a9 9 0 0 1-2.816 0M6.71 19.281a9 9 0 0 1-1.991-1.99M3.11 13.407a9 9 0 0 1 0-2.816M4.719 6.71a9 9 0 0 1 1.99-1.991m3.883-1.608a9 9 0 0 1 2.816 0m3.882 1.608a9 9 0 0 1 1.991 1.99M10 8v8l6-4z");
}

.ft5dv1b6b {
  fill: none;
}

.lxr5h_bko {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16 12l-6 4V8Z");
}

</style>
