<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jk6t-bbtr"/><path class="khwthnbnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-video-two-tone" /></template>
<style>
.jk6t-bbtr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.19907 9.40293L22.19907 12.3993C23.26698 13.19926 23.26698 14.80074 22.19907 15.6007L18.19907 18.59707C16.88045 19.58483 15 18.64393 15 16.99637L15 11.00363C15 9.35607 16.88045 8.41517 18.19907 9.40293Z");
  stroke: none;
}

.khwthnbnc {
  d: path("M2 6H16M2 12H12M2 18H12M17.59977 10.20164L21.59977 13.19983C22.13341 13.59982 22.13341 14.40018 21.59977 14.80017L17.59977 17.79836C16.94049 18.29251 16 17.8221 16 16.99818L16 11.00182C16 10.1779 16.94049 9.70749 17.59977 10.20164Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
