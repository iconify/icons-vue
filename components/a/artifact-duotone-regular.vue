<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ajpcqjbzw"/><path class="m0p17bc4l"/><path class="wzrnw0b2n"/><path class="a9nj5hbth"/><path class="v7bs_s3tb"/><path class="m7goar83z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:artifact-duotone-regular" /></template>
<style>
.a9nj5hbth {
  d: path("M4 11h16");
}

.ajpcqjbzw {
  fill: currentColor;
  d: path("M14 6h3a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m0p17bc4l {
  fill: currentColor;
  d: path("M10 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m7goar83z {
  d: path("M10 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v7bs_s3tb {
  d: path("M12 6v5");
}

.wzrnw0b2n {
  d: path("M14 6h3a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
}

</style>
