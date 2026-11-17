<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m8z0-pbfk"/><path class="klpftq6ck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-dot-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.klpftq6ck {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 13zc0 1 1 1 1 2v2H4v-2c0-1 1-1 1-2V9a6 6 0 0 1 6-6M9 17v1a3 3 0 0 0 6 0v-1m0-11a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.m8z0-pbfk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 13c0 1 1 1 1 2v2h-5v1a3 3 0 1 1-6 0v-1H4v-2c0-1 1-1 1-2V9a6 6 0 0 1 6-6a7.62 7.62 0 0 0 .663 7.224C13.322 12.709 16.175 13.402 19 13");
}

</style>
