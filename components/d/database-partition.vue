<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d0cm20b3y"/><path class="i-7a-zb9i"/><path class="os46fqbjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-partition" /></template>
<style>
.d0cm20b3y {
  d: path("M4 5.5a8 3 0 1 0 16 0a8 3 0 1 0-16 0Z");
}

.i-7a-zb9i {
  d: path("M4 5.5v13a8 3 0 0 0 16 0v-13");
}

.os46fqbjr {
  d: path("M4 12a8 3 0 0 0 16 0m-8-3.5v13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
