<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nw9qmrblx"/><path class="hjuy8p8fb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:geofence-polygon" /></template>
<style>
.hjuy8p8fb {
  d: path("M12 17c-1.25-1.25-3.25-3.5-3.25-6.25a3.25 3.25 0 0 1 6.5 0c0 2.75-2 5-3.25 6.25Zm0-6.25h.01");
}

.nw9qmrblx {
  d: path("m2.5 7.5l7-5L21 5l.5 11.5l-8.5 5l-10-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
