<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6uhj2hoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-matrix-code" /></template>
<style>
.v6uhj2hoh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3v18h18M6 3h.01M9 3h.01M12 3h.01M15 3h.01M18 3h.01M21 3h.01M21 6h.01M21 9h.01M21 12h.01M21 15h.01M21 18h.01M7 7.5h.01m4.49 0h.01M16 10h.01M7 12h.01m4.49 1h.01M16 15h.01M7 16.5h.01m4.49 1h.01");
}

</style>
