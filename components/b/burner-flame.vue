<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdvfbkrzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:burner-flame" /></template>
<style>
.rdvfbkrzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c2.5 3 4 5 4 6.75a4 4 0 0 1-8 0C8 7.5 9.5 5.5 12 2.5Zm-7 19h14L17.5 16h-11Zm4.5-2.75h5");
}

</style>
