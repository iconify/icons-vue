<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq_694bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ironing-board-sharp" /></template>
<style>
.eq_694bmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.25 6.25l.786-2.75H16v2.75ZM3.75 8.5H16c2.75 0 5.25.75 5.25 1.75S18.75 12 16 12H2.75V8.5zm3 3.5L16 21.25M15.75 12L6.5 21.25");
}

</style>
