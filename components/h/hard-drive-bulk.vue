<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="co-ypbb1z"/><path class="adof2ob-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-drive-bulk" /></template>
<style>
.adof2ob-m {
  d: path("M3 12h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m4 3h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2");
}

.co-ypbb1z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 20H5a3 3 0 0 1-3-3v-4c0-.155.036-.308.106-.447l3-6C5.643 5.478 6.652 4.001 8 4h8c1.348.001 2.357 1.478 2.894 2.553l3 6c.07.139.106.292.106.447v4a3 3 0 0 1-3 3M6 16a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
