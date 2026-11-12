<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ye6cy2b2f"/><path class="mo5e-ubjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-close-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mo5e-ubjp {
  d: path("M13.707 6.293L15 7.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L16.414 9l1.293 1.293a.999.999 0 1 1-1.414 1.414L15 10.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L13.586 9l-1.293-1.293a.999.999 0 1 1 1.414-1.414m-11.414 10l3-3a2.415 2.415 0 0 1 3.414 0l7 7a.999.999 0 1 1-1.414 1.414l-7-7a.415.415 0 0 0-.586 0l-3 3a.999.999 0 1 1-1.414-1.414");
}

.ye6cy2b2f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 2a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3Z");
}

</style>
