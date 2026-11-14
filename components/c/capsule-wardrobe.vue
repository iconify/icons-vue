<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e6l-5sb5j"/><path class="uihrkq4hl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:capsule-wardrobe" /></template>
<style>
.e6l-5sb5j {
  d: path("M17 2.5H4.5q-2 0-2 2v15q0 2 2 2H17Zm-9.5 0v19m9.5-19l4.5 2v15l-4.5 2m-9.5-15H17");
}

.uihrkq4hl {
  d: path("M12.25 6.5v2l-2.5 3h5l-2.5-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
