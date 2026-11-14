<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u581u7bvv"/><path class="eeih5-g-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-clover" /></template>
<style>
.eeih5-g-h {
  d: path("M12 13.5c0 3.5 1.5 6 4 8");
}

.u581u7bvv {
  d: path("M9 8.25a3.75 3.75 0 1 1 6 0a3.75 3.75 0 1 1-3 5.25a3.75 3.75 0 1 1-3-5.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
