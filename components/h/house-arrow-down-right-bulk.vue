<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k0z9u4bez"/><path class="t1wm4t86d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-arrow-down-right-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k0z9u4bez {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V19a3 3 0 0 1-3 3");
}

.t1wm4t86d {
  d: path("M15 18h-4a1 1 0 0 1 0-2h1.586l-4.293-4.293a.999.999 0 1 1 1.414-1.414L14 14.586V13a1 1 0 0 1 2 0v4a.997.997 0 0 1-1 1");
}

</style>
