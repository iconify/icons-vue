<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w4frl5svg"/><path class="iw0yty_0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:approval-workflow" /></template>
<style>
.iw0yty_0f {
  d: path("m13 6.25l2 2l-2 2M14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w4frl5svg {
  d: path("M2.5 4.5H9V12H2.5ZM20.8 12H15V4.5h6.5V12h-.3M9 8.25h6");
}

</style>
