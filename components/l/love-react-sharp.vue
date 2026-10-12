<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cglpvermq"/><path class="lwafiwrzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:love-react-sharp" /></template>
<style>
.cglpvermq {
  d: path("M8.3 19.43a8.75 8.75 0 1 0-4.23-4.23l-.67 4.35l-.213 1.281L4.4 20.5Z");
}

.lwafiwrzc {
  d: path("M12 16.25c-1.9-1.55-4.25-3.3-4.25-5.75V8h3.464L12 9.1l.786-1.1h3.464v2.5c0 2.45-2.35 4.2-4.25 5.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
