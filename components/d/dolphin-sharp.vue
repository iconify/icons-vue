<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ozjblsbwb"/><path class="uyeq1yb3w"/><path class="egedvw93v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dolphin-sharp" /></template>
<style>
.egedvw93v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 9.75h.01");
}

.ozjblsbwb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 18.25C6 12 10.5 7.5 15.5 7.5c2.25 0 4 1.25 5 3l.75 1.5h-3.5C12.5 12 8 15 6 19.25Zm.75.5L3 17.5m2.25 1.25l.25 2.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.uyeq1yb3w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 9.5l-.75-4.25l2.766.395L13 7.5l-1.881.602z");
}

</style>
