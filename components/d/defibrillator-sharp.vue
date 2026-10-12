<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="krgq1acbv"/><path class="gtxsc1bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:defibrillator-sharp" /></template>
<style>
.gtxsc1bvt {
  d: path("M8.75 17.5c-2.5-1.75-3.5-3.25-3.5-5.25a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0c0 2-1 3.5-3.5 5.25Zm8.75-8l-2.5 4h3.5l-2.5 4");
}

.krgq1acbv {
  d: path("M8.5 5.75v-3h7v3m-12.75 0h18.5v15H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
