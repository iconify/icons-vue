<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g2y8dlb-i"/><path class="agv1jac2n"/><path class="bbi3-ab3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:care-label" /></template>
<style>
.agv1jac2n {
  d: path("M11 6.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM6.75 11.5L9 17.75h6l2.25-6.25");
}

.bbi3-ab3a {
  d: path("M9.25 14q1.125-1.125 2.25 0t2.25 0c.5-.5.75-.5 1-.5");
}

.g2y8dlb-i {
  d: path("M8 2.5h8L19 6v15H5V6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
