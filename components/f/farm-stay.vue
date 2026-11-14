<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ihf9ztb8f"/><path class="vxjsg5brh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-stay" /></template>
<style>
.ihf9ztb8f {
  d: path("m3 10l3-5l6-2.5L18 5l3 5v11H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vxjsg5brh {
  d: path("M8 21v-8h8v8m-8-8l8 8m0-8l-8 8");
}

</style>
