<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mwjyxhb-l"/><path class="v110pebju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:game-cartridge" /></template>
<style>
.mwjyxhb-l {
  d: path("M4 4.5a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2V15l-1.5 1.5v5h-13v-5L4 15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v110pebju {
  d: path("M7 5.5h10v7H7ZM8.5 19h7");
}

</style>
