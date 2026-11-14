<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ur-gck66t"/><path class="zuep11sta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:indent-hanging" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ur-gck66t {
  d: path("M3.5 4.5h17m-9 5h9m-9 5h9m-9 5h6M4.5 8v4h4");
}

.zuep11sta {
  d: path("M6.75 10.25L8.5 12l-1.75 1.75");
}

</style>
