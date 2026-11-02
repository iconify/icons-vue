<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oavcvx_2p"/><path class="nsfas3bbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nsfas3bbb {
  d: path("M8.315 11.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

.oavcvx_2p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6h3.586l2.707-2.707A1 1 0 0 1 10 3h4c.265 0 .52.105.707.293L17.414 6H21a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1");
}

</style>
