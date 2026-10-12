<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vcr-mxdtk"/><path class="x068t9pwz"/><path class="pox8h1omh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:contour-lines-sharp" /></template>
<style>
.pox8h1omh {
  d: path("m11.76 10.56l.215-.79l.985-.41l1.034-.431l.646.431l.785.524l-.305.916l-.325.975l-1.115.465l-.79.329l-.65-.569l-.705-.617z");
}

.vcr-mxdtk {
  d: path("M3.36 12c-.08-2.08.32-4.52 1.44-6s3.28-2.52 5.28-2.88s4.92-.2 6.72.72s3.52 3.12 4.08 4.8s-.04 3.52-.72 5.28s-1.84 4.12-3.36 5.28s-3.84 1.8-5.76 1.68s-4.48-.92-5.76-2.4s-1.84-4.4-1.92-6.48Z");
}

.x068t9pwz {
  d: path("m8.16 11.52l-.264-2.376L9.6 7.44c.88-.88 2.6-1.12 3.84-1.2l2.601-.168l.999.888l.809.719l-.089 2.401l-.075 2.033l-.885 1.327l-1.097 1.646l-1.783.754l-2.353.995l-1.007-.755c-.96-.72-2.24-3.12-2.4-4.56Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
