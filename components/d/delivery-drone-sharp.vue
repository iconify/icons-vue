<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wkn_-6zay"/><path class="sidhh-bgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:delivery-drone-sharp" /></template>
<style>
.sidhh-bgj {
  d: path("M10.75 12.75v2.75h2.5v-2.75");
}

.wkn_-6zay {
  d: path("M2.75 3.25h5.5m7.5 0h5.5m-15.75 0V6.5H9m9.5-3.25V6.5H15M9 4.75h6V8.5H9zm1.25 3.75l-1 3m4.5-3l1 3m-8 1.25h10.5v8.5H6.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
