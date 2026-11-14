<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lj_ocbc1k"/><path class="nth7w3b3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:benefits-payment" /></template>
<style>
.lj_ocbc1k {
  d: path("M2.5 8h19v13h-19Zm3 0L7 3l12 2l-.75 3");
}

.nth7w3b3o {
  d: path("M21.5 11.5h-4a2 2 0 0 0 0 4h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
