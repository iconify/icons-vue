<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cgyisqbmh"/><path class="ige5w2xiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blocks-duotone" /></template>
<style>
.cgyisqbmh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 3h5a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m1 11a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v6Z");
}

.ft5dv1b6b {
  fill: none;
}

.ige5w2xiz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 14h6a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1zm0 0v7m-7-7h7m4-10a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1Z");
}

</style>
