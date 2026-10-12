<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m7jkanb6w"/><path class="x-h46o_jk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compost-bin-sharp" /></template>
<style>
.m7jkanb6w {
  d: path("M6.25 8.25h13l-.14 1.49l-.97 10.02l-.14 1.49H6l-.14-1.49l-.97-10.02l-.14-1.49zm-3.5-2.5h18.5m-11.5 0v-2.5h4.5v2.5");
}

.x-h46o_jk {
  d: path("M9 18.25c.25-3.5 2-5.5 6-6.25c-.25 3.5-2 5.5-6 6.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
