<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kphxrsb2a"/><path class="mc2ru_bxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:farmhouse-sharp" /></template>
<style>
.kphxrsb2a {
  d: path("M2.75 20.25V11.2l.77-.63l4.21-3.44l.77-.63l.77.63l4.21 3.44l.77.63v10.05H2.75z");
}

.mc2ru_bxr {
  d: path("M6.5 21.25v-5h4v5m-4-5l4 5m0-5l-4 5m10.25 0V7a2.25 2.25 0 0 1 4.5 0v14.25Zm0-10.25h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
