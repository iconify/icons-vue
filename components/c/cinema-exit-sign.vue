<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h2d817bxi"/><path class="s1thihbdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinema-exit-sign" /></template>
<style>
.h2d817bxi {
  d: path("M2.5 6h19v12h-19ZM7 12h9.5");
}

.s1thihbdu {
  d: path("M13.25 8.75L16.5 12l-3.25 3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
