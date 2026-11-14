<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0uxpabcc"/><path class="nrk606b-v"/><path class="q25zkq8_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-map" /></template>
<style>
.nrk606b-v {
  d: path("M12 17.5c-3-3.5-3.5-5-3.5-6.5a3.5 3.5 0 0 1 7 0c0 1.5-.5 3-3.5 6.5Zm-6-14V14m12-4v10.5");
}

.o0uxpabcc {
  d: path("M2.5 3.5h19v17h-19Z");
}

.q25zkq8_v {
  d: path("M10.75 11a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
