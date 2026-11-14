<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f0igy46qs"/><path class="r27q3obnp"/><path class="c37q6ccan"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:certificate-check" /></template>
<style>
.c37q6ccan {
  d: path("M14.75 16.5L16 17.75l2.25-2.5");
}

.f0igy46qs {
  d: path("M9.8 17.5H2.5V4h19v7.9M6 8.5h5M6 12h3.5");
}

.r27q3obnp {
  d: path("M12.5 16.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
