<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xr5637bxf"/><path class="g5do7gb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:glasses-fill" /></template>
<style>
.g5do7gb2a {
  d: path("M10 15C11 13.5 13 13.5 14 15M2.5 13L4.2924 7.9826C4.7424 6.8011 5.6202 5.8924 6.7041 5.486L8 5M21.5 13L19.7076 7.9826C19.2576 6.8011 18.3798 5.8924 17.2959 5.486L16 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xr5637bxf {
  fill: currentColor;
  d: path("M6 10C8.76138 10 11 12.2386 11 15C11 17.7614 8.76138 20 6 20C3.23862 20 1 17.7614 1 15C1 12.2386 3.23862 10 6 10ZM18 10C20.7614 10 23 12.2386 23 15C23 17.7614 20.7614 20 18 20C15.2386 20 13 17.7614 13 15C13 12.2386 15.2386 10 18 10Z");
  stroke: none;
}

</style>
