<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="az6273bfr"/><path class="lgi1e5_im"/><path class="z7hz8fbyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hanger-stack" /></template>
<style>
.az6273bfr {
  d: path("M12 7V6a2 2 0 1 0-2-2m-7 8l9-5l9 5");
}

.lgi1e5_im {
  d: path("m3 15.5l9-5l9 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z7hz8fbyr {
  d: path("m3 19l9-5l9 5H3");
}

</style>
