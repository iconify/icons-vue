<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bqv97e68q"/><path class="zsf37rsiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dollhouse" /></template>
<style>
.bqv97e68q {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17Zm0 3h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zsf37rsiq {
  d: path("M10 7.5h4V11h-4Zm0 13v-4h4v4");
}

</style>
