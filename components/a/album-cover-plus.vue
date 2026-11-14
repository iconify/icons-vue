<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ivy-obc2z"/><path class="c5wqokbjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:album-cover-plus" /></template>
<style>
.c5wqokbjh {
  d: path("M6.75 13a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4.5 0V5L15 6.75M18 15v6m-3-3h6");
}

.ivy-obc2z {
  d: path("M15.2 21.5H2.5v-19h19v12.7m0 5.6v.7h-.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
