<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wpullwedc"/><path class="r1rm97bfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-mirror" /></template>
<style>
.r1rm97bfa {
  d: path("m7.636 13.389l2.475 2.475l-4.42 4.419l-2.474-2.474ZM11 10l3.5-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpullwedc {
  d: path("M7.5 9.5a6.5 7.5 0 1 0 13 0a6.5 7.5 0 1 0-13 0Z");
}

</style>
