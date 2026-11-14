<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w-4nlzq4k"/><path class="hbclf-b8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:foreclosure" /></template>
<style>
.hbclf-b8e {
  d: path("M8 14h8v7H8Zm1.75 0v-1.5a2.25 2.25 0 0 1 4.5 0V14M12 17.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-4nlzq4k {
  d: path("M3 10.5L12 3l9 7.5V21H3Z");
}

</style>
