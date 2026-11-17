<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vnhiw_u-f"/><path class="ct6pm2bdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-off-duotone-round" /></template>
<style>
.ct6pm2bdd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.562 16.562c-.455.278-.99.438-1.562.438H6a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1m6 0h2a3 3 0 0 1 3 3v2m3-2v4M2 2l20 20");
}

.ft5dv1b6b {
  fill: none;
}

.vnhiw_u-f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.562 16.562A3 3 0 0 1 15 17H6a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1ZM13 7h2a3 3 0 0 1 3 3v2Z");
}

</style>
