<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="awo3odbam"/><path class="s2vzoabay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-edit-bulk" /></template>
<style>
.awo3odbam {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H19a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

.cuyn6tgcc {
  fill: currentColor;
}

.s2vzoabay {
  d: path("M8 16v-2c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 11 17H9a1 1 0 0 1-1-1");
}

</style>
