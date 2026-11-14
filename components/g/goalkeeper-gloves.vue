<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jty--sb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:goalkeeper-gloves" /></template>
<style>
.jty--sb1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.5v-16a2.75 2.75 0 0 0-5.5 0v4c-2.5 0-2.75 4 0 5.75v6.25Zm3 0v-16a2.75 2.75 0 0 1 5.5 0v4c2.5 0 2.75 4 0 5.75v6.25ZM5 17.75h5.5m3 0H19");
}

</style>
