<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uk--ombzp"/><path class="whr7-1u1i"/><path class="lqypy4hfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:immunotherapy" /></template>
<style>
.lqypy4hfu {
  d: path("m18 14l3.5 1.25v2.5c0 2-1.5 3.5-3.5 4c-2-.5-3.5-2-3.5-4v-2.5Z");
}

.uk--ombzp {
  d: path("M11.711 14.352L10.75 16L8 14l-3.75-.5L5 10l-.75-3l2.5-1.25L9.5 3l2 2.5l3 .75v3l1.56 2.452m-3.14 1.186l-.387.103");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.whr7-1u1i {
  fill: currentColor;
  d: path("M8 8c1.25-.75 3.25-.5 3.75 1c.25 1.5-.75 3-2.25 2.75S7.25 9 8 8Z");
}

</style>
