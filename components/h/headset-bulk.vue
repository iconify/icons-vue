<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yykf722eo"/><path class="vaddi9b0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:headset-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vaddi9b0z {
  d: path("M5 11a1 1 0 0 1-1-1a8 8 0 0 1 13.657-5.657A7.98 7.98 0 0 1 20 10a1 1 0 0 1-2 0a6 6 0 0 0-1.761-4.247A6 6 0 0 0 6 10a1 1 0 0 1-1 1m14 11h-6a1 1 0 0 1 0-2h6a1 1 0 0 0 1-1v-4a1 1 0 0 1 2 0v4a3.004 3.004 0 0 1-3 3");
}

.yykf722eo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm13 0a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v3a3 3 0 0 1-3 3h-1a3 3 0 0 1-3-3Z");
}

</style>
