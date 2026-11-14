<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7syxxevd"/><path class="w17bvob3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fertility-clinic" /></template>
<style>
.t7syxxevd {
  d: path("M2.5 2.5h11v19h-11ZM8 6v5M5.5 8.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w17bvob3i {
  d: path("M6 21.5V16h4v5.5m8.75 0V15m0 1.5c-2.25 0-2.5-2-2.5-3.5c1.75 0 2.5 1.5 2.5 3.5Zm0-1.5c0-2 1-3.5 3-3.5c0 2-1 3.5-3 3.5Z");
}

</style>
