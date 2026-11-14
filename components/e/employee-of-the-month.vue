<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oj7c2ac2v"/><path class="f_01tmflw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:employee-of-the-month" /></template>
<style>
.f_01tmflw {
  d: path("M9.75 12.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-2 9c0-2.5 2-4 4.25-4s4.25 1.5 4.25 4");
}

.oj7c2ac2v {
  d: path("M4.5 7.5h15v14h-15Zm7.5-5l.823 1.617l1.792.283l-1.284 1.283l.285 1.792L12 6.65l-1.616.825l.285-1.792L9.385 4.4l1.792-.283Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
