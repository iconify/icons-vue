<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zd68_zg5x"/><path class="xd34uo9bs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.xd34uo9bs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 11l4 8c.46.919-.081 2-1 2H5c-.919 0-1.46-1.081-1-2l7-14a1.118 1.118 0 0 1 2 0zM9 9h6m-9 6h12");
}

.zd68_zg5x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20.894 18.553c.181.356.274.75.273 1.149C21.164 20.924 20.265 22 19 22H5c-1.265 0-2.164-1.076-2.167-2.298a2.5 2.5 0 0 1 .273-1.149l7-14a2.116 2.116 0 0 1 3.788 0Z");
}

</style>
