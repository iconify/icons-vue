<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e-ggidwds"/><path class="knpqv1ipd"/><path class="pr-xiqbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bag-carousel" /></template>
<style>
.e-ggidwds {
  d: path("M13.5 21.5h-10V9H18v1.8M5.5 9V6.5a2 2 0 0 1 4 0V9M12 9V6.5a2 2 0 0 1 4 0V9m3.5 6.152A3 3 0 0 1 18 20.75");
}

.knpqv1ipd {
  d: path("M16.5 20.348A3 3 0 0 1 18 14.75");
}

.pr-xiqbis {
  d: path("M16.75 13.5L18 14.75L16.75 16m2.5 3.5L18 20.75L19.25 22");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
