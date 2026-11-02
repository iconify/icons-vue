<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="og9sid0hd"/><path class="wwolfvb3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layout-template-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.og9sid0hd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 14a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm12 0a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Z");
}

.wwolfvb3x {
  d: path("M5 3h14a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2m0 5h14V5H5Z");
}

</style>
