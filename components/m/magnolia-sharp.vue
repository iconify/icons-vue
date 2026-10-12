<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nrmnbr5jy"/><path class="mi-lixcrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magnolia-sharp" /></template>
<style>
.mi-lixcrq {
  d: path("M10.25 7.25c-.25 3 .25 6 1.75 8.5m1.75-8.5c.25 3-.25 6-1.75 8.5M2.75 21l18.5-4.5M12 15.75v3m-6.5 1.58c-2.5-.58-2.75-3.58-2-6.33c2.5 1.25 3.25 3.75 2 6.33Z");
}

.nrmnbr5jy {
  d: path("M12 15.75c-3.5 0-6-2.5-6-6.5v-2.5l.75-1.5l2.286.381L10.25 7.25c.5-2.25 1-3.5 1.75-4.5c.75 1 1.25 2.25 1.75 4.5l1.214-1.619l2.286-.381l.75 1.5v2.5c0 4-2.5 6.5-6 6.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
