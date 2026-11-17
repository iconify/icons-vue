<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t6adk3bze"/><path class="m6l85xbdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:external-link-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m6l85xbdq {
  d: path("M14 18h3a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1H7a.997.997 0 0 0-1 1v3a1 1 0 0 1-2 0V7a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3h-3a1 1 0 0 1 0-2m-4 2a1 1 0 0 1-2 0v-2.586l-4.293 4.293a.999.999 0 1 1-1.414-1.414L6.586 16H4a1 1 0 0 1 0-2h5a1 1 0 0 1 1 1Z");
}

.t6adk3bze {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 19V7a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2Z");
}

</style>
