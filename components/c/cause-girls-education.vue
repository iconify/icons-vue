<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fhwfnpbfn"/><path class="bxf3edcfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cause-girls-education" /></template>
<style>
.bxf3edcfr {
  d: path("M7.5 7v3c2.5 1.5 6.5 1.5 9 0V7M12 14.5v7.25M20.5 5.5V10");
}

.fhwfnpbfn {
  d: path("M12 14.5q-3-1.5-9-.75V21q6-.75 9 .75q3-1.5 9-.75v-7.25q-6-.75-9 .75Zm-8.5-9l8.5-3l8.5 3l-8.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
