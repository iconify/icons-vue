<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b1gttpbzo"/><path class="ko18k2bkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corner-down-right" /></template>
<style>
.b1gttpbzo {
  d: path("M4.5 4.5V11A3.5 3.5 0 0 0 8 14.5h11.5");
}

.ko18k2bkg {
  d: path("m14.5 9.5l5 5l-5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
