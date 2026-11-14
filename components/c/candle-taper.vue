<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf0mus_qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:candle-taper" /></template>
<style>
.gf0mus_qm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 8.5h3V17h-3ZM9 17h6v2H9Zm3 2v2m-5 0h10M12 5.75C10.85 5 10.75 3.6 12 2c1.25 1.6 1.15 3 0 3.75Z");
}

</style>
