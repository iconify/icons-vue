<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s_2ghabqu"/><path class="ches287iv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-duotone-sharp" /></template>
<style>
.ches287iv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3v4l5 5l-5 5v4M17 3v4l-5 5l5 5v4M5 3h14M5 21h14");
}

.ft5dv1b6b {
  fill: none;
}

.s_2ghabqu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 3h10v4l-5 5l-5-5Zm0 14l5-5l5 5v4H7Z");
}

</style>
