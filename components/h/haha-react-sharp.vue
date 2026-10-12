<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cglpvermq"/><path class="f8p2oqc2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:haha-react-sharp" /></template>
<style>
.cglpvermq {
  d: path("M8.3 19.43a8.75 8.75 0 1 0-4.23-4.23l-.67 4.35l-.213 1.281L4.4 20.5Z");
}

.f8p2oqc2f {
  d: path("M8 9.75L9.25 8.5l1.25 1.25m3 0l1.25-1.25L16 9.75m-8 2.5h8a4 4 0 0 1-8 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
