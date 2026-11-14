<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rcjcord1g"/><path class="h0of5-b6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fat-macro" /></template>
<style>
.h0of5-b6k {
  d: path("M15.75 13a4 4 0 0 1 .25 3.5");
}

.rcjcord1g {
  d: path("M12 3s-7.25 7.5-7.25 11.25a7.25 7.25 0 0 0 14.5 0C19.25 10.5 12 3 12 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
