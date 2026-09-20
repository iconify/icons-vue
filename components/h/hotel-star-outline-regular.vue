<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d5czi6rdr"/><path class="e_zu0lb2f"/><path class="rju00-nqb"/><path class="s09hy0b0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hotel-star-outline-regular" /></template>
<style>
.d5czi6rdr {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.e_zu0lb2f {
  d: path("M10 22v-5h4v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rju00-nqb {
  d: path("m12 5.5 2 2 -2 2 -2 -2Z");
}

.s09hy0b0y {
  d: path("M7 11h10");
}

</style>
