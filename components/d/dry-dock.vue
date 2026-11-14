<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b5j-_fbnq"/><path class="k_-bicc8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dry-dock" /></template>
<style>
.b5j-_fbnq {
  d: path("M3 4.5v15h18v-15");
}

.k_-bicc8z {
  d: path("M6 8h12l-2 7.5H8Zm4 7.5v4m4-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
