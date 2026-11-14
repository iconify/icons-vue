<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aarw6cciy"/><path class="dmfhc4pca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-phone-sign" /></template>
<style>
.aarw6cciy {
  d: path("M4 2.5h16A1.5 1.5 0 0 1 21.5 4v16a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20V4A1.5 1.5 0 0 1 4 2.5Z");
}

.dmfhc4pca {
  d: path("M8.25 6.5H10l1 3l-1.5 1c.75 1.5 2.25 3 3.75 3.75l1.25-1.5l3 1v2a1.75 1.75 0 0 1-1.75 1.75c-5.25 0-9.25-4-9.25-9.25A1.75 1.75 0 0 1 8.25 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
