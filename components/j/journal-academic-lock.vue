<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r1ocxjbcb"/><path class="seao0j_ez"/><path class="loqt-jbch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:journal-academic-lock" /></template>
<style>
.loqt-jbch {
  d: path("M11.5 8v2.5q2 1.25 4 0V8m-.5 9.5h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.r1ocxjbcb {
  d: path("M12.2 21.5H3.5v-19H19v9.8M7 2.5v19");
}

.seao0j_ez {
  d: path("m13.5 5.5l3.25 1.75L13.5 9l-3.25-1.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
