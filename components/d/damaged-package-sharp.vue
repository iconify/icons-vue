<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lc6cpri-v"/><path class="lj2ej1xdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:damaged-package-sharp" /></template>
<style>
.lc6cpri-v {
  d: path("M20.25 7.65v8.7l-.016.886l-.784.414l-6.55 3.4l-.9.454l-.9-.454l-6.55-3.4l-.784-.414l-.016-.886v-8.7l.016-.886l.784-.414l6.55-3.4l.9-.454l.9.454l6.55 3.4l.784.414z");
}

.lj2ej1xdl {
  d: path("m4 7.25l8 4l8-4m-8 4v9M7.75 4.75L16 9.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
