<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ftnaqly3h"/><path class="hevy9xxmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:concrete-pump-truck" /></template>
<style>
.ftnaqly3h {
  d: path("M2.5 16.5v-3h12v-5h4l3 3.5v4.5Z");
}

.hevy9xxmd {
  d: path("m4.5 13.5l3-10l4.25 3.75L19.5 3v3m-15 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
