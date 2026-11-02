<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gfs57itka"/><path class="u-t2g1brr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gfs57itka {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5c0-.898.572-1.928 1.521-2.089a1.34 1.34 0 0 1 1.186.382l3 3c.948.948 3.638.948 4.586 0l3-3c.31-.311.752-.456 1.186-.382C19.428 3.072 20 4.102 20 5v4.838l.949 2.846c.119.359.026.755-.242 1.023l-7 7a2.414 2.414 0 0 1-3.414 0l-7-7a1 1 0 0 1-.242-1.023L4 9.838Z");
}

.u-t2g1brr {
  d: path("M10.707 12.293a.999.999 0 1 1-1.414 1.414l-1-1a.999.999 0 1 1 1.414-1.414Zm4 1.414a.999.999 0 1 1-1.414-1.414l1-1a.999.999 0 1 1 1.414 1.414ZM12.01 15a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
