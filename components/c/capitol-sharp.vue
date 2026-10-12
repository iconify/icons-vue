<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u7kg6yqst"/><path class="svfgbfbfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:capitol-sharp" /></template>
<style>
.svfgbfbfl {
  d: path("M12 8.5V2.75h3m-5.5 14v2.5m2.5-2.5v2.5m2.5-2.5v2.5M5.5 17v2m13-2v2");
}

.u7kg6yqst {
  d: path("M2.75 21.25v-7h4.5V12.5H8a4 4 0 0 1 8 0h.75v1.75h4.5v7Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
