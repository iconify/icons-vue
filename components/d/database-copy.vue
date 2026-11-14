<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k1r3jrvwd"/><path class="d6qw6eo4b"/><path class="co_gj4azy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-copy" /></template>
<style>
.co_gj4azy {
  d: path("M10 3.2A6.5 2.5 0 0 1 21 5v10a6.5 2.5 0 0 1-2.25 1.9");
}

.d6qw6eo4b {
  d: path("M3 9v9.5a6.5 2.5 0 0 0 13 0V9");
}

.k1r3jrvwd {
  d: path("M3 9a6.5 2.5 0 1 0 13 0A6.5 2.5 0 1 0 3 9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
