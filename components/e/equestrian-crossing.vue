<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl684bcef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:equestrian-crossing" /></template>
<style>
.zl684bcef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.5h9.5L16.75 5l.75-2l1 2.25l3 3.5l-1.25 1.5l-2.5-.75l-1.25 6H4Zm2 5v6m8.5-6v6M4 11l-1.5 5M8.25 4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM10 5.75v4.75");
}

</style>
