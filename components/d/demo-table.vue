<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pfg1y-bxy"/><path class="cavhasbmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:demo-table" /></template>
<style>
.cavhasbmo {
  d: path("m3 7l9 4.5l.213-.106m1.52-.761L21 7m-9 4.5v10M7.5 4.75l9 4.5M15 14.5l6.5 3.5l-6.5 3.5Z");
}

.pfg1y-bxy {
  d: path("m12.201 21.4l-.201.1L3 17V7l9-4.5L21 7v7.538");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
