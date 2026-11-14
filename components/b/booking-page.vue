<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ncev7ghqi"/><path class="juoe7ubkp"/><path class="kfj-2om_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:booking-page" /></template>
<style>
.juoe7ubkp {
  d: path("M6.5 6.5h11v8h-11Zm3-1.25v2.5m5-2.5v2.5");
}

.kfj-2om_c {
  d: path("M10.5 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ncev7ghqi {
  d: path("M2.5 2.5h19v15h-19Zm9.5 15V21m-4 0h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
