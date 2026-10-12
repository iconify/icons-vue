<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="g9tav7hfl"/><path class="r2jnhoaem"/><path class="rsgshebrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cabin-house-sharp" /></template>
<style>
.g9tav7hfl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20.5v-9H2.75l.58-.47l8.09-6.56L12 4l.58.47l8.09 6.56l.58.47H20v9.75H4zm0-5.75h5m6 0h5M4 18h5m6 0h5");
}

.r2jnhoaem {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.25h.01");
}

.rsgshebrg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 21.25v-5.5h4v5.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
