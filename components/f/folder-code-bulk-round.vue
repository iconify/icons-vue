<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2axkab4k"/><path class="zoqrycbnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-code-bulk-round" /></template>
<style>
.a2axkab4k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H17a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

.cuyn6tgcc {
  fill: currentColor;
}

.zoqrycbnw {
  d: path("M7.293 13.707a.997.997 0 0 1 0-1.414l2-2a.999.999 0 1 1 1.414 1.414L9.414 13l1.293 1.293a.999.999 0 1 1-1.414 1.414Zm9.414-1.414a1 1 0 0 1 0 1.414l-2 2a.999.999 0 1 1-1.414-1.414L14.586 13l-1.293-1.293a.999.999 0 1 1 1.414-1.414Z");
}

</style>
