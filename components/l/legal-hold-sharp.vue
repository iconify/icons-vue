<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uiu_jkbcv"/><path class="kt47z8t9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:legal-hold-sharp" /></template>
<style>
.kt47z8t9q {
  d: path("M14.25 2.75v5h5m-8.75 3.5v6.5m3-6.5v6.5");
}

.uiu_jkbcv {
  d: path("M6.75 2.75h7.5l5 5v13.5H4.75V2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
