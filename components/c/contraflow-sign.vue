<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="em74ppb7h"/><path class="wwjs67byu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contraflow-sign" /></template>
<style>
.em74ppb7h {
  d: path("m12 2.5l10 18H2Zm-2.25 10v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wwjs67byu {
  d: path("m8.75 16.5l1 1l1-1m3-4v5m-1-4l1-1l1 1");
}

</style>
