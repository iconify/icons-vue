<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v_48wv89y"/><path class="jhl96-b7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guest-feedback" /></template>
<style>
.jhl96-b7m {
  d: path("m12 6.25l1 2.5l2.75.25l-2 1.75l.5 2.75L12 12l-2.25 1.5l.5-2.75l-2-1.75L11 8.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_48wv89y {
  d: path("M4.5 3.5h15a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2H10l-4.5 3.5V17h-1a2 2 0 0 1-2-2V5.5a2 2 0 0 1 2-2Z");
}

</style>
