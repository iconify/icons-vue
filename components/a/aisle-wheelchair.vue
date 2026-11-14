<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s6jaxpb2n"/><path class="ogbf3cb8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aisle-wheelchair" /></template>
<style>
.ogbf3cb8o {
  d: path("M3.5 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm13.75 4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.s6jaxpb2n {
  d: path("M3 4h3.5v9H16l3 4.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
