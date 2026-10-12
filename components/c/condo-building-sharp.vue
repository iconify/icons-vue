<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y6jqtbcwp"/><path class="ft0-jod-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:condo-building-sharp" /></template>
<style>
.ft0-jod-p {
  d: path("M7 21.25v-2.5h3v2.5m7.25-14h4v14h-4zm0 4.5h4m-4 4.5h4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6jqtbcwp {
  d: path("M2.75 2.75h11.5v18.5H2.75zm3 4.25h5.5m-5.5 4h5.5m-5.5 4h5.5");
}

</style>
