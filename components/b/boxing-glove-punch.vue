<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9sunrb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boxing-glove-punch" /></template>
<style>
.q9sunrb9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 7V5.5h4.5A5.5 5.5 0 0 1 21 11v1.5a5.5 5.5 0 0 1-5.5 5.5H11v-1.5H9.25a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1Zm0 0v9.5m0-4h5m-13.5-3h3m-3 4.5h3");
}

</style>
