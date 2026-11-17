<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="csb3qoyml"/><path class="z76tfcczh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-duotone-round" /></template>
<style>
.csb3qoyml {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 20V7a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v13Z");
}

.ft5dv1b6b {
  fill: none;
}

.z76tfcczh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18m-9 0V7a3 3 0 0 0-3-3H8a3 3 0 0 0-3 3v13m7-9.4l.126-.1a3 3 0 0 1 3.748 0l1.625 1.299A4 4 0 0 1 19 14.923V20");
}

</style>
