<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q6mx6p8ck"/><path class="cpjucyb5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:detour-route" /></template>
<style>
.cpjucyb5e {
  d: path("M18.75 12.25L21.5 15l-2.75 2.75");
}

.q6mx6p8ck {
  d: path("M2.5 15H6c2 0 2-9 6-9s4 9 6 9h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
