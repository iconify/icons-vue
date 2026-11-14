<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e_krceh5v"/><path class="n3uv-tb6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brand-guidelines" /></template>
<style>
.e_krceh5v {
  d: path("M12 5.5Q9 3.25 3 4v14.5q6-.75 9 1.5Zm0 0q3-2.25 9-1.5v14.5q-6-.75-9 1.5");
}

.n3uv-tb6u {
  d: path("M6 8h3v3H6Zm9 1h3m-3 4h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
