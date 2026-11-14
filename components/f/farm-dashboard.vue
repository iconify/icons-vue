<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q84mzdbvw"/><path class="bsq-2mbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-dashboard" /></template>
<style>
.bsq-2mbvl {
  d: path("M12.75 14.5a3 3 0 0 1 6 0m-3 0l1.75-2.25");
}

.q84mzdbvw {
  d: path("M2.5 4.5h19v15h-19Zm3.75 12V12m3 4.5v-8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
