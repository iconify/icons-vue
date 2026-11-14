<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fgq5wxbhy"/><path class="feh94fb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lymphatic-system" /></template>
<style>
.feh94fb1h {
  d: path("M8.5 8.5c0 2.5 7-2 7 .5m0 6c0 2.5-7-2-7 .5");
}

.fgq5wxbhy {
  d: path("M6 5.5a2.5 3 0 1 0 5 0a2.5 3 0 1 0-5 0Zm7 6.5a2.5 3 0 1 0 5 0a2.5 3 0 1 0-5 0Zm-7 6.5a2.5 3 0 1 0 5 0a2.5 3 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
