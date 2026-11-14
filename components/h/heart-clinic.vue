<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fr0ihabpq"/><path class="ucn4u8auy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-clinic" /></template>
<style>
.fr0ihabpq {
  d: path("M2.5 7h19v14.5h-19Zm0 0l2-3.5h15l2 3.5");
}

.ucn4u8auy {
  d: path("M12 14.75S9.25 13 9.25 11.25c0-.75.75-1.5 1.5-1.5c.5 0 1 .5 1.25.75c.25-.25.75-.75 1.25-.75c.75 0 1.5.75 1.5 1.5c0 1.75-2.75 3.5-2.75 3.5Zm-2 6.75v-4h4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
