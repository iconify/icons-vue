<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k_9de8b7z"/><path class="i6l7ot9yu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:goal-alignment" /></template>
<style>
.i6l7ot9yu {
  d: path("M6.5 14.25v4.5h11v-4.5m-11-4.5h.01m10.99 0h.01m-11.01 0l4.5-4.5m6.5 4.5l4-4");
}

.k_9de8b7z {
  d: path("M2 9.75a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm11 0a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
