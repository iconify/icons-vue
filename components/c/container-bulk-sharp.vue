<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m2dtcxzwn"/><path class="vwnh6tbbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:container-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m2dtcxzwn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1");
}

.vwnh6tbbw {
  d: path("M9 19a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>
