<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dv54uh0ex"/><path class="n3edwr-zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baklava" /></template>
<style>
.dv54uh0ex {
  d: path("m12 2.5l9.5 4.25v9L12 20l-9.5-4.25v-9Z");
}

.n3edwr-zb {
  d: path("M2.5 6.75L12 11l9.5-4.25m-19 4.5L12 15.5l9.5-4.25m-5.5 7V20a1.25 1.25 0 0 0 2.5 0v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
