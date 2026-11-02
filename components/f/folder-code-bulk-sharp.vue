<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ub4z9ebsg"/><path class="zoqrycbnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-code-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ub4z9ebsg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 3c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Z");
}

.zoqrycbnw {
  d: path("M7.293 13.707a.997.997 0 0 1 0-1.414l2-2a.999.999 0 1 1 1.414 1.414L9.414 13l1.293 1.293a.999.999 0 1 1-1.414 1.414Zm9.414-1.414a1 1 0 0 1 0 1.414l-2 2a.999.999 0 1 1-1.414-1.414L14.586 13l-1.293-1.293a.999.999 0 1 1 1.414-1.414Z");
}

</style>
