<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u57yq2bni"/><path class="u-2pw6blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:backup-shield-sharp" /></template>
<style>
.u-2pw6blj {
  d: path("M14.6 9.75a3 3 0 1 0 .4 2m-.25-4V10H12.5");
}

.u57yq2bni {
  d: path("m12 2.75l6.6 2.45l.652.244l-.002.696v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14l-.002-.696L5.4 5.2Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
