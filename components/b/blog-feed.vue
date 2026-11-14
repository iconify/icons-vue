<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dkiuagkns"/><path class="dy_4oxbkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blog-feed" /></template>
<style>
.dkiuagkns {
  d: path("M12.7 21.5H4.5v-19h15v11.1");
}

.dy_4oxbkb {
  d: path("M7.5 5.5h9V10h-9Zm0 7.5h5.2m-5.2 4H11m4.5 4.5h.01m-.01-3a3 3 0 0 1 3 3m-3-6a6 6 0 0 1 6 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
