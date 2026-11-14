<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v5d6ig_0q"/><path class="qozrjqb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:circuit" /></template>
<style>
.qozrjqb6y {
  d: path("M16 13a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM8.75 3.5v5m2.75-4v3M17 11l4 4m0-4l-4 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5d6ig_0q {
  d: path("M8.75 6H5a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-2m0-6V8a2 2 0 0 0-2-2h-5.5");
}

</style>
