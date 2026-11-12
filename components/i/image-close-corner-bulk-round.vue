<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xn4n-1bjv"/><path class="m22bp6pgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-close-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m22bp6pgz {
  d: path("M13 8a2 2 0 1 1 3.999-.001A2 2 0 0 1 13 8M2.293 16.293l4-4A3.82 3.82 0 0 1 9 11.171a3.82 3.82 0 0 1 2.707 1.122a.999.999 0 1 1-1.414 1.414a1.83 1.83 0 0 0-2.586 0l-4 4a.999.999 0 1 1-1.414-1.414m14.414-1L18 16.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L19.414 18l1.293 1.293a.999.999 0 1 1-1.414 1.414L18 19.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L16.586 18l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

.xn4n-1bjv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12h-6c-.796 0-1.559.316-2.121.879A3 3 0 0 0 12 15v6a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a1 1 0 0 1-1 1");
}

</style>
