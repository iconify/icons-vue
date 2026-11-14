<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ey9s5ab8y"/><path class="uwni876fg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-premium" /></template>
<style>
.ey9s5ab8y {
  d: path("m3 9l4-5h10l4 5l-9 10.5Zm0 0h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwni876fg {
  d: path("M8.5 9L12 4l3.5 5m-7 0L12 19.5L15.5 9");
}

</style>
