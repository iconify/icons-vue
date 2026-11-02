<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cd4xz4odh"/><path class="tm-7tqbxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eject-bulk" /></template>
<style>
.cd4xz4odh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4.456 12.41l5-8a3 3 0 0 1 5.088 0l5 8A2.999 2.999 0 0 1 17 17H7a3 3 0 0 1-2.544-4.59");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tm-7tqbxw {
  d: path("M5 19h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2");
}

</style>
