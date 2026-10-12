<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="s5bfmnb8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-merge-sharp" /></template>
<style>
.rh2140hgr {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.s5bfmnb8c {
  d: path("M13.75 2.75v5.5h5.5m-10 2V11c0 2 2.75 2 2.75 4v3.5m2.75-8.25V11c0 2-2.75 2-2.75 4m-1.75 2L12 18.75L13.75 17");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
