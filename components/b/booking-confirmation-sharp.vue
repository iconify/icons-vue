<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mp_9z4b7a"/><path class="hfebp-bde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:booking-confirmation-sharp" /></template>
<style>
.hfebp-bde {
  d: path("m9.25 6.5l2 2L15 4.75M8.5 12h1.25m1.65 0h1.25m1.6 0h1.25m-7 4.5h7");
}

.mp_9z4b7a {
  d: path("M4.75 4.75v-2h14.5v7a2.25 2.25 0 0 0 0 4.5v7H4.75v-7a2.25 2.25 0 0 0 0-4.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
