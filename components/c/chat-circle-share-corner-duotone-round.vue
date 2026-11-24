<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h1y38cbhk"/><path class="ohnaambnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-share-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h1y38cbhk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 8a4 4 0 0 0-4 4v8l-5 1l1-5a8.945 8.945 0 0 1 16-8Z");
}

.ohnaambnf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 20l-5 1l1-5a8.944 8.944 0 1 1 16-8m-4 6h4v4m0-4l-6 6");
}

</style>
