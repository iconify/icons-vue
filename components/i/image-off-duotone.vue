<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="md_py4wny"/><path class="biv_jxw5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-duotone" /></template>
<style>
.biv_jxw5w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.414 20.414A2 2 0 0 1 19 21H5a2 2 0 0 1-2-2V5c0-.552.224-1.052.586-1.414M9 3h10a2 2 0 0 1 2 2v10M3 17l7-7m5-2a1 1 0 1 0 2 0a1 1 0 0 0-2 0M2 2l20 20");
}

.ft5dv1b6b {
  fill: none;
}

.md_py4wny {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 3h10a2.003 2.003 0 0 1 2 2v10Zm11.414 17.414c-.378.378-.88.589-1.414.586H5a2.003 2.003 0 0 1-2-2V5c0-.535.205-1.038.586-1.414Z");
}

</style>
