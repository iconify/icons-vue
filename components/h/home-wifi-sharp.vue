<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="r8ny-mbmd"/><path class="lxh-mlb2t"/><path class="r8i1ocbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:home-wifi-sharp" /></template>
<style>
.lxh-mlb2t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.29 13.54a5.25 5.25 0 0 1 7.42 0m-5.65 1.77L12 13.379l1.94 1.931");
}

.r8i1ocbvm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.25h.01");
}

.r8ny-mbmd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.75L12 3.25l8.25 6.5v10.5H3.75v-2Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
