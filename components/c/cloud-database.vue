<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="us4aecctx"/><path class="b-gf3qr4p"/><path class="y5x0gufjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloud-database" /></template>
<style>
.b-gf3qr4p {
  d: path("M5.5 13.25v6.25a6.5 2 0 0 0 13 0v-6.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.us4aecctx {
  d: path("M8.75 8.5a2.25 2.25 0 0 1 0-4.5a3.5 3.5 0 0 1 6.25.5a2 2 0 0 1 .25 4ZM5.5 13.25a6.5 2 0 1 0 13 0a6.5 2 0 1 0-13 0Z");
}

.y5x0gufjb {
  d: path("M5.5 16.5a6.5 2 0 0 0 13 0");
}

</style>
