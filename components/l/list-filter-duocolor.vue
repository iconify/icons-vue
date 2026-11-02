<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jwvpjsz2r"/><path class="k4qo1xe9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-filter-duocolor" /></template>
<style>
.jwvpjsz2r {
  stroke-opacity: 0.4;
  d: path("M7 12h10m-7 6h4");
}

.k4qo1xe9v {
  d: path("M4 6h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
