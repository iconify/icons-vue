<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dn80ut9fg"/><path class="q6w20pbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ferry-route-sharp" /></template>
<style>
.dn80ut9fg {
  d: path("M3.5 14.25h10.75l-.34.67l-1.07 2.16l-.34.67h-8l-.34-.67l-1.07-2.16l-.34-.67z");
}

.q6w20pbxx {
  d: path("M6 14.25v-3h5v3m-7.75 7c1.5 0 1.75-.75 3.25-.75s1.75.75 3.25.75s1.75-.75 3.25-.75s1.75.75 3.25.75M14 10c1.5-2.5 3.5-4.25 7-5m-2.75-1.75L21 5l-1.5 2.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
