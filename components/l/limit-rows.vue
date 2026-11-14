<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ufkw6fvrl"/><path class="gqkmm4aci"/><path class="d_newem_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:limit-rows" /></template>
<style>
.d_newem_b {
  d: path("M3 19.5h3.5m3 0h5m3 0H21");
}

.gqkmm4aci {
  fill: currentColor;
  d: path("M2 12h20v2.5H2Z");
}

.ufkw6fvrl {
  d: path("M3 3.5h18M3 8h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
