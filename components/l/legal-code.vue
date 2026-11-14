<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u0twtl96g"/><path class="n6s_k8nig"/><path class="s7axybcmk"/><path class="qs381ordp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:legal-code" /></template>
<style>
.n6s_k8nig {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5M14 6.5a2 1.25 0 1 0-2 1.25");
}

.qs381ordp {
  d: path("M10 12.5a2 1.25 0 1 0 2-1.25");
}

.s7axybcmk {
  d: path("M10.25 9.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.u0twtl96g {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
