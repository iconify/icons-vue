<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hb80twj7w"/><path class="k7ao077nd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hearse-car" /></template>
<style>
.hb80twj7w {
  d: path("M2.5 15.5v-9A1.5 1.5 0 0 1 4 5h10l3.5 4.5H20a1.5 1.5 0 0 1 1.5 1.5v4.5Z");
}

.k7ao077nd {
  d: path("M5.5 8h6v3h-6Zm-1 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
