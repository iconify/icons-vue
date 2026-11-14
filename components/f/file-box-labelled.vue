<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cq8jo2bli"/><path class="wadq_6blm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:file-box-labelled" /></template>
<style>
.cq8jo2bli {
  d: path("M4 8v11a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8M4 8l2.5-4h11L20 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wadq_6blm {
  d: path("M9 12h6v3.5H9Z");
}

</style>
