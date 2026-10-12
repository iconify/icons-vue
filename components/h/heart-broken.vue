<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wh5ahubit"/><path class="u0w8rt-ho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heart-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u0w8rt-ho {
  d: path("M12 6.5L10.75 10l2.5 2.75l-1.5 3.75");
}

.wh5ahubit {
  d: path("M12 20.25c-.4 0-.8-.15-1.1-.4C7.6 17.1 3.25 13.6 3.25 8.9C3.25 6.2 5.3 4 7.9 4c1.6 0 3 .8 4.1 2.2C13.1 4.8 14.5 4 16.1 4c2.6 0 4.65 2.2 4.65 4.9c0 4.7-4.35 8.2-7.65 10.95c-.3.25-.7.4-1.1.4");
}

</style>
