<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sz6uj-b_h"/><path class="zthitrbkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:computer-cleaning" /></template>
<style>
.sz6uj-b_h {
  d: path("M13.5 19.6v1.9H3v-19h10.5v9.4M6 6.5h4.5M6 9.5h4.5m-2.25 7h.01m8.24 5v-3a1 1 0 0 1 1-1V14h3v3.5a1 1 0 0 1 1 1v3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zthitrbkd {
  d: path("M17.5 14.75h-2.25v2");
}

</style>
