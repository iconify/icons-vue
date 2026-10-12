<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri41r1cyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:leaning-tower-sharp" /></template>
<style>
.ri41r1cyc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21.25h5.75l.11-.74L16.7 8.24l.11-.74h-6.5l-.11.74l-1.84 12.27l-.11.74zM11.81 7.5h4l.07-.49l.42-2.77l.07-.49h-4.5l-.07.49l-.42 2.77l-.07.49zM8.78 17.75h6.5m-5.98-3.5h6.5m-5.97-3.5h6.5m-9.58 10.5h10.5");
}

</style>
