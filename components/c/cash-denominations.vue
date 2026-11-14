<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d-mm4kb-n"/><path class="bn6p61bue"/><path class="l11-wkzpu"/><path class="u-3tsfd1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-denominations" /></template>
<style>
.bn6p61bue {
  d: path("M11.5 15h-4A1.5 1.5 0 0 1 6 13.5v-4A1.5 1.5 0 0 1 7.5 8H16a1.5 1.5 0 0 1 1.5 1.5v4");
}

.d-mm4kb-n {
  d: path("M11.5 13.5h10v6h-10Z");
}

.l11-wkzpu {
  d: path("M6 10H4a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 4 3h10a1.5 1.5 0 0 1 1.5 1.5V8m-1 8.5a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0ZM8 11.25a1.75 1 0 1 0 3.5 0a1.75 1 0 1 0-3.5 0Z");
}

.u-3tsfd1l {
  d: path("M7 5.5a1.75 1 0 1 0 3.5 0a1.75 1 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
