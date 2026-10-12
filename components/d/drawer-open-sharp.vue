<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmgjh-m4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drawer-open-sharp" /></template>
<style>
.lmgjh-m4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25h17.5V19.5H3.25zm0 5.5h17.5m-17.5 5.5h17.5M10.5 6h3m-3 5.5h3m-3 5.4h3M6 19.5v1.75m12-1.75v1.75");
}

</style>
