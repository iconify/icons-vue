<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oue9j_brx"/><path class="cwqkrjd2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-merge-sharp" /></template>
<style>
.cwqkrjd2s {
  d: path("m6.5 14l4.1 2.65l1.4.906l1.4-.906L17.5 14M5.75 2.75C5.75 5 12 4 12 6v3.5m6.25-6.75C18.25 5 12 4 12 6M9.75 7.25L12 9.5l2.25-2.25");
}

.oue9j_brx {
  d: path("M2.75 11h18.5v9.25H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
