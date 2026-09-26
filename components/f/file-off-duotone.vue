<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vfy9zwu-h"/><path class="is41me23v"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.is41me23v {
  stroke-opacity: 0.4;
  d: path("M7.6703 2.01C7.779 2 7.889 2 8 2L14 2L20 8L20 14.3431M20 8L17 8C15.34 8 14 6.6569 14 5L14 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vfy9zwu-h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.3919 20.3919C19.5438 21.9458 17.895 23 16 23H8C5.2386 23 3 20.76 3 18V6C3 5.1336 3.2204 4.3186 3.6081 3.6081L20.3919 20.3919Z");
  stroke: none;
}

</style>
