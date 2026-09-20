<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG1BbAvbzp)" class="cy07ctgrm"/><defs><linearGradient id="SVG1BbAvbzp" x1="11.678" x2="11.678" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="xyat4ib1w"/><stop offset="1" class="b5zrdhctb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hibs" /></template>
<style>
.b5zrdhctb {
  stop-color: var(--svg-color--1a75bb, #1a75bb);
}

.cy07ctgrm {
  d: path("M5.25 3A2.25 2.25 0 0 0 3 5.25v13.5a2.25 2.25 0 0 0 4.5 0V5.25A2.25 2.25 0 0 0 5.25 3M12 5.584a2.25 2.25 0 0 0-2.25 2.257v8.337a2.25 2.25 0 0 0 4.5 0V7.842A2.25 2.25 0 0 0 12 5.584m4.5 6.056c0-1.222 1.01-2.211 2.25-2.211s2.25.99 2.25 2.211v7.148C21 20.01 19.99 21 18.75 21a2.23 2.23 0 0 1-2.25-2.212zM18.75 3a2.25 2.25 0 1 0 0 4.5a2.25 2.25 0 0 0 0-4.5");
}

.ft5dv1b6b {
  fill: none;
}

.xyat4ib1w {
  stop-color: var(--svg-color--25a9e0, #25a9e0);
}

</style>
