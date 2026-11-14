<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cwyag7hjm"/><path class="i4y_-7upl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:histology" /></template>
<style>
.cwyag7hjm {
  d: path("M2.5 5.5h19v13h-19Zm15.5 0v13");
}

.i4y_-7upl {
  d: path("m7.5 9l2.5 1.5v3L7.5 15L5 13.5v-3Zm2.5 1.5L12.5 9l2.5 1.5v3L12.5 15L10 13.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
