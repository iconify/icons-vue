<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="twozt5b6p"/><path class="cex9sd-5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:child-vaccine" /></template>
<style>
.cex9sd-5l {
  d: path("M17.5 16.25c0-.75 1.25-.75 1.25.25s-1.5 1.25-2 .25");
}

.twozt5b6p {
  d: path("m13.768 4.697l3.535 3.535l-7.071 7.071l-3.535-3.535ZM8.5 13.5L4 18M15.5 6.5L18 4m-1.5-1.5l3 3m-4.25 11.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM18 19.5v2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
