<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o6jb8yb7y"/><path class="d9rsgr4ju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:files-grid-sharp" /></template>
<style>
.d9rsgr4ju {
  d: path("M8.25 2.75h7.5l4.5 4.5v10.5");
}

.o6jb8yb7y {
  d: path("M12.25 5.75h-8.5v15.5h12.5V9.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
