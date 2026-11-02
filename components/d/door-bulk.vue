<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z0kktyjuc"/><path class="fyemarmgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:door-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fyemarmgs {
  d: path("M14 11h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m7 9a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

.z0kktyjuc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a1 1 0 0 1-1-1V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v16a1 1 0 0 1-1 1");
}

</style>
