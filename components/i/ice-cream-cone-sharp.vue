<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3yuydact"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ice-cream-cone-sharp" /></template>
<style>
.k3yuydact {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9.5a6 6 0 0 1 12 0ZM7.5 13h10l-.55.83l-4.4 6.59l-.55.83l-.55-.83l-4.4-6.59L6.5 13z");
}

</style>
