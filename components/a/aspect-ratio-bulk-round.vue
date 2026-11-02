<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n3ea6gw5u"/><path class="rrht3cb0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:aspect-ratio-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n3ea6gw5u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Z");
}

.rrht3cb0i {
  d: path("M6 12v-1a3 3 0 0 1 3-3h1a1 1 0 0 1 0 2H9a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0m12 0v1a3 3 0 0 1-3 3h-1a1 1 0 0 1 0-2h1a.997.997 0 0 0 1-1v-1a1 1 0 0 1 2 0");
}

</style>
