<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w29z0rb2l"/><path class="zvob9cxwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-screening" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w29z0rb2l {
  d: path("M6 21.5V6a3.5 3.5 0 0 1 3.5-3.5h5A3.5 3.5 0 0 1 18 6v15.5m-14.5 0h17");
}

.zvob9cxwm {
  d: path("M8.75 10h1.5l1.25-3l1.5 6l1.25-3h1M9.5 17h5");
}

</style>
