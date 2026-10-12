<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fs8on6yat"/><path class="os7w2mblx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coloring-book-sharp" /></template>
<style>
.fs8on6yat {
  d: path("M12 6.5c-2-1.5-5-2-9.25-1.75v13.5C7 18 10 18.5 12 20c2-1.5 5-2 9.25-1.75V4.75C17 4.5 14 5 12 6.5Zm0 0v13");
}

.os7w2mblx {
  d: path("M16.75 8a2 2 0 1 1 0 4a2 2 0 1 1 0-4Zm-3 7L15 13.75L16.25 15l1.25 1.25L18.75 15M5 10.25h4M5 13.5h4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
