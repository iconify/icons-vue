<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="letc5acoj"/><path class="cp3579-vf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:facial-roller" /></template>
<style>
.cp3579-vf {
  d: path("M6.5 5.25H5V8.5a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V5.25h-1.5M12 10.5V17m-3.5 0h7v4h-7Z");
}

.letc5acoj {
  d: path("M6.5 3h11v4.5h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
