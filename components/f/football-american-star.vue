<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3bo8xbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:football-american-star" /></template>
<style>
.g3bo8xbuc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.93 15.95C7.913 16.951 5.571 17.5 3 17.5C3 9 9 3 17.5 3c0 4.454-1.648 8.222-4.44 10.8m-4.81-1.55l4-4m-4 2l2 2m0-4l2 2m5.5 3.75l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
