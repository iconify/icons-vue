<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ee7fr_buz"/><path class="r0opx9bnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:funny-car" /></template>
<style>
.ee7fr_buz {
  d: path("M3.5 14v-3H9l2.5-3H14l2.5 3l5 1.25V14Zm2-3V5.5m-3 0H8");
}

.r0opx9bnv {
  d: path("M4.5 16.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM16 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
