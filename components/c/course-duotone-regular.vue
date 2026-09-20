<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z0gsc-gzi"/><path class="abneybc_z"/><path class="kfroy-4bw"/><path class="o9o4t05de"/><path class="ec-jcit8z"/><path class="ugs22v-bb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:course-duotone-regular" /></template>
<style>
.abneybc_z {
  fill: currentColor;
  d: path("M5 10h14v4H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ec-jcit8z {
  d: path("M5 10h14v4H5Z");
}

.kfroy-4bw {
  fill: currentColor;
  d: path("M7 17h14v4H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o9o4t05de {
  d: path("M3 3h14v4H3Z");
}

.ugs22v-bb {
  d: path("M7 17h14v4H7Z");
}

.z0gsc-gzi {
  fill: currentColor;
  d: path("M3 3h14v4H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
