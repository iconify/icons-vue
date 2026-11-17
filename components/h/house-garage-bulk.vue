<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k0z9u4bez"/><path class="mw3rl6gwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-garage-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k0z9u4bez {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V19a3 3 0 0 1-3 3");
}

.mw3rl6gwu {
  d: path("M7 17v-2a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v6a1 1 0 0 1-2 0v-3H9v3a1 1 0 0 1-2 0Zm2-1h6v-1a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1Z");
}

</style>
