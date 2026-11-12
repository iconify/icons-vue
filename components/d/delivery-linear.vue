<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vdgidnnsf"/><path class="v1r-x4bqc"/><circle class="n7e8zdwmr"/><path class="ssy2ybbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:delivery-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n7e8zdwmr {
  cx: 8.05px;
  cy: 18.1px;
  r: 2.9px;
}

.ssy2ybbtv {
  d: path("M10.9199 17.36L19.9999 15");
}

.v1r-x4bqc {
  d: path("M8.23 15.0602L6.08 7.27014C5.89453 6.61732 5.38563 6.12036 4.7 5.92L3 5.4502");
}

.vdgidnnsf {
  d: path("M14.9484 13.3188L16.8683 12.8199C18.6784 12.3495 19.5834 12.1143 19.995 11.4227C20.4067 10.7312 20.1642 9.85343 19.6792 8.09786L19.1647 6.2358C18.6797 4.48023 18.4372 3.60244 17.7242 3.20319C17.0113 2.80394 16.1062 3.03915 14.2962 3.50955L12.3763 4.00849C10.5662 4.47889 9.66119 4.71409 9.24954 5.40562C8.8379 6.09714 9.0804 6.97492 9.56541 8.73049L10.0798 10.5926C10.5648 12.3481 10.8073 13.2259 11.5203 13.6252C12.2333 14.0244 13.1384 13.7892 14.9484 13.3188Z");
}

</style>
