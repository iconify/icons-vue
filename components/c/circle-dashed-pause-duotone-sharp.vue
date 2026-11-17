<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce8i36bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-pause-duotone-sharp" /></template>
<style>
.ce8i36bjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.89 10.592a9 9 0 0 1 0 2.816m-1.61 3.882a9 9 0 0 1-1.99 1.991m-3.883 1.608a9 9 0 0 1-2.816 0M6.71 19.281a9 9 0 0 1-1.991-1.99M3.11 13.407a9 9 0 0 1 0-2.816M4.719 6.71a9 9 0 0 1 1.99-1.991m3.883-1.608a9 9 0 0 1 2.816 0m3.882 1.608a9 9 0 0 1 1.991 1.99M10 9v6m4-6v6");
}

</style>
