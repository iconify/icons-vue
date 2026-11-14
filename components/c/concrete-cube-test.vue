<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fdan5fv6d"/><path class="vtmibdvzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:concrete-cube-test" /></template>
<style>
.fdan5fv6d {
  d: path("M3 4h18M3 20h18M12 4l6.75 4v8L12 20l-6.75-4V8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vtmibdvzj {
  d: path("M5.25 8L12 12l6.75-4M12 12v8");
}

</style>
