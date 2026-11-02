<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2axkab4k"/><path class="g6ptozzor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-close-bulk-round" /></template>
<style>
.a2axkab4k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H17a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

.cuyn6tgcc {
  fill: currentColor;
}

.g6ptozzor {
  d: path("m12 11.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 13l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 14.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 13l-1.293-1.293a.999.999 0 1 1 1.414-1.414Z");
}

</style>
