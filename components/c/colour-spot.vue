<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="jjq03gkep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colour-spot" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.jjq03gkep {
  fill: currentColor;
  d: path("M12 7s3.5 3.5 3.5 6a3.5 3.5 0 0 1-7 0c0-2.5 3.5-6 3.5-6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
