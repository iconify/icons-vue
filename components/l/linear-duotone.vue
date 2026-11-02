<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t410u2ncb"/><path class="m75auvbbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:linear-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m75auvbbu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3.307 9.67l11.022 11.023M3.898 15.92l4.183 4.183M5.292 6a9 9 0 1 1 12.709 12.709Z");
}

.t410u2ncb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.293 19.415L4.585 6.707a1 1 0 0 1-.038-1.374a9.998 9.998 0 0 1 17.449 6.945a10 10 0 0 1-3.329 7.175a1 1 0 0 1-1.374-.038");
}

</style>
