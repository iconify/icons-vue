<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":267};
const content = `<defs><filter id="SVGvMS3qcAV" width="200%" height="200%" x="-50%" y="-50%" filterUnits="objectBoundingBox"><feOffset dy="1" in="SourceAlpha" result="shadowOffsetOuter1"/><feGaussianBlur in="shadowOffsetOuter1" result="shadowBlurOuter1" stdDeviation="2"/><feColorMatrix in="shadowBlurOuter1" result="shadowMatrixOuter1" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.243359375 0"/><feMerge><feMergeNode in="shadowMatrixOuter1"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><path class="y3fm5ef0x"/><path class="r6uesmb7z"/><path class="bugfuab9u"/><path filter="url(#SVGvMS3qcAV)" transform="translate(4 3)" class="kcpv5--6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:grove" /></template>
<style>
.bugfuab9u {
  fill: var(--svg-color--92c83e, #92c83e);
  d: path("m102.098 236.12l93.138-190.133s30.31 34.72 37.475 50.702c6.613 14.88 4.96 47.947-5.511 73.849s-31.964 45.19-44.089 50.15c-50.151 22.045-81.013 15.432-81.013 15.432");
}

.kcpv5--6q {
  fill: var(--svg-color--fff, #fff);
  d: path("M248 124C248 55.662 192.338 0 124 0S0 55.662 0 124c0 62.827 47.396 115.182 108.569 122.898v13.226l25.902-12.675C197.85 242.489 248 189.03 248 124M124 225.956c-52.907 0-101.956-49.05-101.956-101.956S71.094 22.044 124 22.044S225.956 71.094 225.956 124S176.906 225.956 124 225.956");
}

.r6uesmb7z {
  fill: var(--svg-color--4b843d, #4b843d);
  d: path("m59.662 212.422l67.236-131.164l36.373 68.338l-51.804 89.83z");
}

.y3fm5ef0x {
  fill: var(--svg-color--92c83e, #92c83e);
  d: path("m37.067 181.009l35.27-67.787l28.107 47.396l-35.822 57.315z");
}

</style>
