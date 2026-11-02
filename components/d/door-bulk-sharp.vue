<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qqk49bd6r"/><path class="fyemarmgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:door-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fyemarmgs {
  d: path("M14 11h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m7 9a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

.qqk49bd6r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Z");
}

</style>
