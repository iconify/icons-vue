<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mfr_1obew"/><path class="bh1uc5kuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:harbour-office" /></template>
<style>
.bh1uc5kuj {
  d: path("M7.5 20.5v-5h4v5m8.5 0V3m0 0l-4.5 1.75L20 6.5Z");
}

.mfr_1obew {
  d: path("m2.5 11l7-6l7 6v9.5h-14Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
