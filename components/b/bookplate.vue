<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u0twtl96g"/><path class="pwik2zbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bookplate" /></template>
<style>
.pwik2zbwn {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h5m-2-11h5A1.5 1.5 0 0 0 16.5 7v4a1.5 1.5 0 0 0-1.5 1.5h-5A1.5 1.5 0 0 0 8.5 11V7A1.5 1.5 0 0 0 10 5.5ZM11 9h3");
}

.u0twtl96g {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
