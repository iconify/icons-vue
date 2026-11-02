<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dys5ohbwa"/><path class="ylp8e6x0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:escape-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dys5ohbwa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6.414V8a1 1 0 0 1-2 0V4a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2H6.414l6.293 6.293a.999.999 0 1 1-1.414 1.414Z");
}

.ylp8e6x0u {
  d: path("M15.504 3.708c4.578 1.934 6.721 7.216 4.786 11.795c-1.934 4.578-7.215 6.724-11.794 4.789a8.9 8.9 0 0 1-2.86-1.928a8.9 8.9 0 0 1-1.928-2.86A8.9 8.9 0 0 1 3 12a1 1 0 0 1 2 0a6.9 6.9 0 0 0 .55 2.724a7.002 7.002 0 0 0 12.9 0A7 7 0 0 0 12 5a1 1 0 0 1 0-2a8.9 8.9 0 0 1 3.504.708");
}

</style>
